# Metro 2 Dispute Tool

## Overview
The Metro 2 Dispute Tool is a comprehensive solution designed to streamline the process of credit report parsing, Metro 2 compliant file generation, and the creation of Letters of Intent to Sue (LOITS). Optimized for small business use, this tool provides both a command-line interface (CLI) and a web interface to handle large files, integrate AI-powered analysis via FinBERT, and produce dynamic, personalized dispute letters.

## Features
- **Credit Report Parsing**: 
  - Fetch reports via API or parse local files (XML, CSV, JSON)
  - Optimized for large files with streaming and chunked processing
  - Graceful handling of unsupported formats and robust error logging
- **Metro 2 File Generation**:
  - Generates fully compliant files with dynamic segment inclusion (Header, Base, J1, J2, K1, Trailer)
  - Memory-efficient processing and field validation
- **LOITS Generator**:
  - Creates personalized Letters of Intent to Sue using dynamic data and AI-powered sentiment analysis
  - Integrates with FinBERT to analyze dispute reasons and include evaluation labels
- **CLI & Web Interface**:
  - User-friendly CLI built with Typer for clear command structure and input validation
  - FastAPI-based web interface (with potential for secure authentication and asynchronous job status tracking)
- **Performance Optimizations**:
  - Asynchronous I/O and batch processing for large datasets
  - Model reuse for FinBERT to minimize initialization overhead

## Directory Structure
# gdai
