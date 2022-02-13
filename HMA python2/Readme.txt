Backtrader library is self-contained with no external dependencies (except if you want to plot)

Features:   Live Trading and backtesting platform written in Python.

        Live Data Feed and Trading with
            Interactive Brokers (needs IbPy and benefits greatly from an installed pytz)
            Visual Chart (needs a fork of comtypes until a pull request is integrated in the release and benefits from pytz)
            Oanda (needs oandapy) (REST API Only - v20 did not support streaming when implemented)
        Data feeds from csv/files, online sources or from pandas and blaze
        Filters for datas, like breaking a daily bar into chunks to simulate intraday or working with Renko bricks
        Multiple data feeds and multiple strategies supported
        Multiple timeframes at once
        Integrated Resampling and Replaying
        Step by Step backtesting or at once (except in the evaluation of the Strategy)
        Integrated battery of indicators
        TA-Lib indicator support (needs python ta-lib / check the docs)
        Easy development of custom indicators
        Analyzers (for example: TimeReturn, Sharpe Ratio, SQN) and pyfolio integration (deprecated)
        Flexible definition of commission schemes
        Integrated broker simulation with Market, Close, Limit, Stop, StopLimit, StopTrail, StopTrailLimit*and *OCO orders, bracket order, slippage, volume filling strategies and continuous cash adjustmet for future-like instruments
        Sizers for automated staking
        Cheat-on-Close and Cheat-on-Open modes
        Schedulers
        Trading Calendars
        Plotting (requires matplotlib)





To start with: cmd or vscode terminal

        pip install backtrader

        pip install backtrader[plotting]

        If matplotlib is not installed and you wish to do some plotting

to test the strategy : 
go to folder tests and run the test_ind_hma.py


It'll run multiple time to stop it use ctrl+c or ctrl+x
