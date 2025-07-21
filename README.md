
# セットアップ
python -m pip install -e .

# 全テスト実行
pytest tests/

# 詳細表示
pytest -v tests/

# 特定のテスト
pytest tests/test_calculator.py::test_add

# カバレッジ付き（要pytest-cov）
pytest --cov=calculator tests/