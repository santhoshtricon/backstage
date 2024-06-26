## API Report File for "@backstage/plugin-app-backend"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts
import { Config } from '@backstage/config';
import { ConfigSchema } from '@backstage/config-loader';
import express from 'express';
import { Logger } from 'winston';
import { PluginDatabaseManager } from '@backstage/backend-common';

// @public (undocumented)
export function createRouter(options: RouterOptions): Promise<express.Router>;

// @public (undocumented)
export interface RouterOptions {
  appPackageName: string;
  // (undocumented)
  config: Config;
  database?: PluginDatabaseManager;
  disableConfigInjection?: boolean;
  // (undocumented)
  logger: Logger;
  schema?: ConfigSchema;
  staticFallbackHandler?: express.Handler;
}
```
