# FacebookFeed
- A demo app Implements limited feature of Facebook using Progressive Web App!

##LIGHTHOUSE
<html lang="en"><head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1">
  <link rel="icon" href="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAIAAAD8GO2jAAADjklEQVR4AWI08P/HQEvAQrxSQKvlECfLFYXx75xCY2qmh89GbNvOMjb3v9jOOlxnFWxj206ebQ3b7q6q+z1rNagu8/zvPSZACAABpeUAA0miMgU7SA7JjCraFGwZwECOwvL75dWjsKgWBKtx0jvWo+vkBAFbACCkByMP6nMn48+AVgXB2fzSCwsv22/lMGlUhmJ0AE7BH8dyUUDbUEgN6RzJRSeaPxhdRYR0Inel+7Hd5lBiFpkMAxACc0394//9C4voFHDiAAGLpuOXebdfdHfctgwJKaZRLRKy6ItrSis6RBnVBgGtbHyKTEmJHQoEXoBCE5BCrDeA2ogMUIGDAKEBDEhUqwgMqBYDjW4DQzmuffVdqff42/ZQYYqVcMXGZsMPyCsH3lyJSetxvEaxAQXdjR1HjfwCdIS7lo2DZke26Qe+MXO12OWkGT0O6oE7vMGkMnkYw4aN1KQgMKExhXqswfiov4+a7MQ11XPnbr/5qpKlgACAAQj94Lu271bN9DUecQasIZlNzG72llRAAKJiAi+/BSHrSFjRvQhg3DEKEqJh08tsmLTx597+f6enr4cc2Zpk57pihfX24dW7RHcOLLUbJYhJSl0ErQCI9BVXH/XrO97QasuvQQSiECa0BrQCIIJp6X9T/r8QG6L71WYSqCoIIGo2BZDUBnS/D9EA9Nun1iYvbM0MFExIDQRoKFatc1Z6zrm5uWeObJotq0BGV9FuQBWq5a4Fw3PPz848rZHstZSuA5FWAFSMP2nOppOOGpl6qh9PCSg0IFyHKjSQyDNQHTru2t75NOEe0fsf246oAmFkI6vCdnWvbQFQFCKx8vCswV8TrDLiDLgH4Nr7RAtNsrC9d8sfk7b8ls4igdNy8CQKAISlsB0FjZfd3Lfp155tf8fKI4BxZZIj/oTdVEAIAcJFOCmzauHG71I7/rdreUAgAqpDP05fDARCAQQARwEIBQSVxq0FyaLvZZtevpHa8WHw8cft6cpxlq8eAJtIhnSbWDf951yx3y13OqUuu5qyGgkxCgGFh9cDihDGbTa6BqvT1lWmrav3bmt2ZMJ4mU6TGgIC4DBzcv/JqAau1WhzSt3x9Ixk/4Jk/8J4ZrrViFMA4W6A7+WK8xcVjvyrOmVD0FbAXokcT48r+xVqLKvuJYbmpNadnlp3mpufJHOe/GXktM+r09bT8kEdq9BRYAbGSgzP7ll82U71Mc+ZFooXgwAAAABJRU5ErkJggg==">
  <title>Lighthouse Report</title>
  <style>/**
 * @license Copyright 2017 Google Inc. All Rights Reserved.
 * Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0
 * Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
 */

.lh-vars {
  --text-font-family: Roboto, Helvetica, Arial, sans-serif;
  --monospace-font-family: 'Menlo', 'dejavu sans mono', 'Consolas', 'Lucida Console', monospace;
  --body-font-size: 14px;
  --body-line-height: 18px;
  --subheader-font-size: 16px;
  --subheader-line-height: 20px;
  --header-font-size: 20px;
  --header-line-height: 24px;
  --title-font-size: 24px;
  --title-line-height: 28px;
  --caption-font-size: 12px;
  --caption-line-height: 16px;
  --default-padding: 12px;
  --section-padding: 20px;
  --section-indent: 16px;
  --audit-group-indent: 16px;
  --audit-indent: 16px;
  --expandable-indent: 20px;
  --secondary-text-color: #565656;
  /*--accent-color: #3879d9;*/
  --fail-color: #df332f;
  --pass-color: #2b882f;
  --informative-color: #0c50c7;
  --manual-color: #757575;
  --average-color: #ef6c00; /* md orange 800 */
  --warning-color: #ffab00; /* md amber a700 */
  --report-border-color: #ccc;
  --report-secondary-border-color: #ebebeb;
  --metric-timeline-rule-color: #b3b3b3;
  --report-width: calc(60 * var(--body-font-size));
  --report-menu-width: calc(20 * var(--body-font-size));
  --report-content-width: calc(var(--report-width) + var(--report-menu-width));
  --navitem-font-size: var(--body-font-size);
  --navitem-line-height: var(--body-line-height);
  --navitem-hpadding: var(--body-font-size);
  --navitem-vpadding: calc(var(--navitem-line-height) / 2);
  --lh-score-highlight-bg: hsla(0, 0%, 90%, 0.2);
  --lh-score-icon-background-size: 24px;
  --lh-score-margin: 12px;
  --lh-table-header-bg: hsla(0, 0%, 50%, 0.4);
  --lh-table-higlight-bg: hsla(0, 0%, 75%, 0.1);
  --lh-sparkline-height: 5px;
  --lh-sparkline-thin-height: 3px;
  --lh-filmstrip-thumbnail-width: 60px;
  --lh-audit-score-width: calc(5 * var(--body-font-size));
  --lh-category-score-width: calc(5 * var(--body-font-size));
  --lh-audit-vpadding: 8px;
  --lh-audit-hgap: 12px;
  --lh-audit-group-vpadding: 12px;
  --lh-section-vpadding: 12px;
  --pass-icon-url: url('data:image/svg+xml;utf8,<svg width="12" height="12" viewBox="0 0 12 12" xmlns="http://www.w3.org/2000/svg"><path stroke="%23007F04" stroke-width="1.5" d="M1 5.75l3.5 3.5 6.5-6.5" fill="none" fill-rule="evenodd"/></svg>');
  --fail-icon-url: url('data:image/svg+xml;utf8,<svg width="12" height="12" viewBox="0 0 12 12" xmlns="http://www.w3.org/2000/svg"><g stroke="%23EE1D0A" stroke-width="1.5" fill="none" fill-rule="evenodd"><path d="M2 10l8-8M10 10L2 2"/></g></svg>');
  --collapsed-icon-url: url('data:image/svg+xml;utf8,<svg width="12" height="12" viewBox="0 0 12 12" xmlns="http://www.w3.org/2000/svg"><g fill="none" fill-rule="evenodd"><path fill="none" d="M0 0h12v12H0z"/><path fill="hsl(0, 0%, 60%)" d="M3 2l6 4-6 4z"/></g></svg>');
  --expanded-icon-url: url('data:image/svg+xml;utf8,<svg width="12" height="12" viewBox="0 0 12 12" xmlns="http://www.w3.org/2000/svg"><g fill="none" fill-rule="evenodd"><path fill="none" d="M0 0h12v12H0z"/><path fill="hsl(0, 0%, 60%)" d="M10 3L6 9 2 3z"/></g></svg>');
}

.lh-vars.lh-devtools {
  --text-font-family: '.SFNSDisplay-Regular', 'Helvetica Neue', 'Lucida Grande', sans-serif;
  --monospace-font-family: 'Menlo', 'dejavu sans mono', 'Consolas', 'Lucida Console', monospace;
  --body-font-size: 12px;
  --body-line-height: 16px;
  --subheader-font-size: 14px;
  --subheader-line-height: 18px;
  --header-font-size: 16px;
  --header-line-height: 20px;
  --title-font-size: 20px;
  --title-line-height: 24px;
  --caption-font-size: 11px;
  --caption-line-height: 14px;
  --default-padding: 12px;
  --section-padding: 16px;
  --section-indent: 16px;
  --audit-group-indent: 16px;
  --audit-indent: 16px;
  --expandable-indent: 16px;

  --lh-audit-vpadding: 4px;
  --lh-audit-hgap: 12px;
  --lh-audit-group-vpadding: 8px;
  --lh-section-vpadding: 8px;
}

@keyframes fadeIn {
  0% { opacity: 0;}
  100% { opacity: 0.6;}
}

.lh-root * {
  box-sizing: border-box;
}

.lh-root {
  font-family: var(--text-font-family);
  font-size: var(--body-font-size);
  margin: 0;
  line-height: var(--body-line-height);
  background: #f5f5f5;
  scroll-behavior: smooth;
}

.lh-root :focus {
    outline: -webkit-focus-ring-color auto 3px;
}

.lh-root [hidden] {
  display: none !important;
}

a {
  color: #0c50c7;
}

summary {
  cursor: pointer;
}

.lh-details {
  font-size: var(--body-font-size);
  margin-top: var(--default-padding);
}

.lh-details[open] summary {
  margin-bottom: var(--default-padding);
}

.lh-details summary::-webkit-details-marker {
  color: #9e9e9e;
}

.lh-details.flex .lh-code {
  max-width: 70%;
}

/* Report header */

.report-icon {
  opacity: 0.7;
}
.report-icon:hover {
  opacity: 1;
}
.report-icon[disabled] {
  opacity: 0.3;
  pointer-events: none;
}

.report-icon--share {
  background-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path fill="none" d="M0 0h24v24H0z"/><path d="M18 16.08c-.76 0-1.44.3-1.96.77L8.91 12.7c.05-.23.09-.46.09-.7s-.04-.47-.09-.7l7.05-4.11c.54.5 1.25.81 2.04.81 1.66 0 3-1.34 3-3s-1.34-3-3-3-3 1.34-3 3c0 .24.04.47.09.7L8.04 9.81C7.5 9.31 6.79 9 6 9c-1.66 0-3 1.34-3 3s1.34 3 3 3c.79 0 1.5-.31 2.04-.81l7.12 4.16c-.05.21-.08.43-.08.65 0 1.61 1.31 2.92 2.92 2.92 1.61 0 2.92-1.31 2.92-2.92s-1.31-2.92-2.92-2.92z"/></svg>');
}
.report-icon--print {
  background-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path d="M19 8H5c-1.66 0-3 1.34-3 3v6h4v4h12v-4h4v-6c0-1.66-1.34-3-3-3zm-3 11H8v-5h8v5zm3-7c-.55 0-1-.45-1-1s.45-1 1-1 1 .45 1 1-.45 1-1 1zm-1-9H6v4h12V3z"/><path fill="none" d="M0 0h24v24H0z"/></svg>');
}
.report-icon--copy {
  background-image: url('data:image/svg+xml;utf8,<svg height="24" viewBox="0 0 24 24" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M0 0h24v24H0z" fill="none"/><path d="M16 1H4c-1.1 0-2 .9-2 2v14h2V3h12V1zm3 4H8c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h11c1.1 0 2-.9 2-2V7c0-1.1-.9-2-2-2zm0 16H8V7h11v14z"/></svg>');
}
.report-icon--open {
  background-image: url('data:image/svg+xml;utf8,<svg height="24" viewBox="0 0 24 24" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M0 0h24v24H0z" fill="none"/><path d="M19 4H5c-1.11 0-2 .9-2 2v12c0 1.1.89 2 2 2h4v-2H5V8h14v10h-4v2h4c1.1 0 2-.9 2-2V6c0-1.1-.89-2-2-2zm-7 6l-4 4h3v6h2v-6h3l-4-4z"/></svg>');
}
.report-icon--download {
  background-image: url('data:image/svg+xml;utf8,<svg height="24" viewBox="0 0 24 24" width="24" xmlns="http://www.w3.org/2000/svg"><path d="M19 9h-4V3H9v6H5l7 7 7-7zM5 18v2h14v-2H5z"/><path d="M0 0h24v24H0z" fill="none"/></svg>');
}

/* List */
.lh-list {
  font-size: smaller;
  margin-top: var(--default-padding);
}

.lh-list__items {
  padding-left: var(--default-padding);
}

.lh-list__item {
  margin-bottom: 2px;
}

/* Node */
.lh-node {
  display: block;
  font-family: var(--monospace-font-family);
  word-break: break-word;
  color: hsl(174, 100%, 27%);
}
span.lh-node:hover {
    background: hsl(0, 0%, 98%);
    border-radius: 2px;
}

/* Card */
.lh-scorecards {
  display: flex;
  flex-wrap: wrap;
}
.lh-scorecard {
  display: flex;
  align-items: center;
  justify-content: center;
  flex: 0 0 calc(12 * var(--body-font-size));
  flex-direction: column;
  padding: var(--default-padding);
  padding-top: calc(32px + var(--default-padding));
  border-radius: 3px;
  margin-right: var(--default-padding);
  position: relative;
  line-height: inherit;
  border: 1px solid #ebebeb;
}
.lh-scorecard__title {
  background-color: #eee;
  position: absolute;
  top: 0;
  right: 0;
  left: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: calc(var(--default-padding) / 2);
}
.lh-scorecard__value {
  font-size: calc(1.6 * var(--body-font-size));
}
.lh-scorecard__target {
  margin-top: calc(var(--default-padding) / 2);
}

/* Score */

.lh-score {
  display: flex;
  align-items: flex-start;
}

.lh-score__value {
  flex: none;
  margin-left: var(--lh-score-margin);
  width: calc(var(--lh-audit-score-width) - var(--lh-score-margin));
  position: relative;
  font-weight: bold;
  top: 1px;
  text-align: right;
}

.lh-score__value::after {
  content: '';
  position: absolute;
  right: 0;
  top: 0;
  bottom: 0;
  border-radius: inherit;
  width: 16px;
}

.lh-score--informative .lh-score__value {
  color: var(--informative-color);
  border-radius: 50%;
  top: 3px;
}

.lh-score--informative .lh-score__value::after {
  display: none;
  background: url('data:image/svg+xml;utf8,<svg width="24" height="24" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><title>info</title><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm1 15h-2v-6h2v6zm0-8h-2V7h2v2z" fill="hsl(218, 89%, 41%)"/></svg>') no-repeat 50% 50%;
  background-size: var(--lh-score-icon-background-size);
}

.lh-score--manual .lh-score__value::after {
  background: url('data:image/svg+xml;utf8,<svg width="12" height="12" viewBox="0 0 12 12" xmlns="http://www.w3.org/2000/svg"><title>manual</title><path d="M2 5h8v2H2z" fill="hsl(0, 0%, 100%)" fill-rule="evenodd"/></svg>') no-repeat 50% 50%;
  background-size: 18px;
  background-color: var(--manual-color);
  width: 20px;
  height:  20px;
  position: relative;
}

.lh-score__value--binary {
  color: transparent !important;
}

/* No icon for audits with number scores. */
.lh-score__value:not(.lh-score__value--binary)::after {
  content: none;
}

.lh-score__value--pass {
  color: var(--pass-color);
}

.lh-score__value--pass::after {
  background: var(--pass-icon-url) no-repeat center center / 12px 12px;
}

.lh-score__value--average {
  color: var(--average-color);
}

.lh-score__value--average::after {
  background: none;
  content: '!';
  color: var(--average-color);
  display: flex;
  justify-content: center;
  align-items: center;
  font-weight: 500;
  font-size: 15px;
}

.lh-score__value--fail {
  color: var(--fail-color);
}

.lh-score__value--fail::after {
  background: var(--fail-icon-url) no-repeat center center / 12px 12px;
}

.lh-score__description {
  font-size: var(--body-font-size);
  color: var(--secondary-text-color);
  line-height: var(--body-line-height);
}

.lh-score__snippet {
  align-items: center;
  justify-content: space-between;
  /*outline: none;*/
}

.lh-score__snippet::-moz-list-bullet {
  display: none;
}

.lh-score__title {
  flex: 1;
}

.lh-toggle-arrow {
  background: var(--collapsed-icon-url) no-repeat center center / 12px 12px;
  background-color: transparent;
  width: 12px;
  height: 12px;
  flex: none;
  transition: transform 150ms ease-in-out;
  cursor: pointer;
  border: none;
  order: -1;
  margin-right: calc(var(--expandable-indent) - 12px);
  align-self: flex-start;
}

.lh-toggle-arrow-unexpandable {
  visibility: hidden;
}

/* Expandable Details (Audit Groups, Audits) */

.lh-score__header {
  order: -1;
  flex: 1;
}

.lh-expandable-details {
  padding-left: var(--expandable-indent);
}

.lh-expandable-details__summary {
  display: flex;
  align-items: center;
  cursor: pointer;
  margin-left: calc(0px - var(--expandable-indent));
}

.lh-audit-group[open] > .lh-audit-group__summary > .lh-toggle-arrow,
.lh-expandable-details[open] > .lh-expandable-details__summary > .lh-toggle-arrow {
  background-image: var(--expanded-icon-url);
}

.lh-audit-group__summary::-webkit-details-marker,
.lh-expandable-details__summary::-webkit-details-marker {
  display: none;
}

.lh-score__snippet .lh-toggle-arrow {
  margin-top: calc((var(--body-line-height) - 12px) / 2);
}

/* Perf Timeline */

.lh-timeline-container {
  overflow: hidden;
  border-top: 1px solid var(--metric-timeline-rule-color);
}

.lh-timeline {
  padding: 0;
  padding-bottom: 0;
  width: calc(var(--lh-filmstrip-thumbnail-width) * 10 + var(--default-padding) * 2);
}

.lh-narrow .lh-timeline-container {
  width: calc(100vw - var(--section-padding) * 2);
  overflow-x: scroll;
}

.lh-devtools .lh-timeline-container {
  width: 100%;
  overflow-x: scroll;
}

/* Perf Timeline Metric */

.lh-timeline-metric {
  position: relative;
  margin-bottom: calc(2 * var(--lh-audit-vpadding));
  padding-top: var(--lh-audit-vpadding);
  border-top: 1px solid var(--report-secondary-border-color);
}

.lh-timeline-metric__header {
  display: flex;
}

.lh-timeline-metric__details {
  order: -1;
}

.lh-timeline-metric__title {
  font-size: var(--body-font-size);
  line-height: var(--body-line-height);
  display: flex;
}

.lh-timeline-metric__name {
  flex: 1;
}

.lh-timeline-metric__description {
  color: var(--secondary-text-color);
}

.lh-timeline-metric__value {
  width: var(--lh-audit-score-width);
  text-align: right;
}

.lh-timeline-metric--pass .lh-timeline-metric__value {
  color: var(--pass-color);
}

.lh-timeline-metric--average .lh-timeline-metric__value {
  color: var(--average-color);
}

.lh-timeline-metric--fail .lh-timeline-metric__value {
  color: var(--fail-color);
}

.lh-timeline-metric__sparkline {
  position: absolute;
  left: 0;
  right: 0;
  top: -1px;
  height: 3px;
  width: 100%;
}

.lh-timeline-metric__sparkline .lh-sparkline__bar {
  float: none;
}

.lh-timeline-metric--pass .lh-sparkline__bar {
  background: var(--pass-color);
}

.lh-timeline-metric--average .lh-sparkline__bar {
  background: var(--average-color);
}

.lh-timeline-metric--fail .lh-sparkline__bar {
  background: var(--fail-color);
}

.lh-timeline-metric .lh-debug {
  margin-left: var(--expandable-indent);
}

/* Perf Hint */

.lh-perf-hint {
  padding-top: var(--lh-audit-vpadding);
  padding-bottom: var(--lh-audit-vpadding);
  border-top: 1px solid var(--report-secondary-border-color);
}

.lh-perf-hint:last-of-type {
  border-bottom: none;
}

.lh-perf-hint__summary {
  display: flex;
  align-items: flex-start;
  flex-wrap: wrap;
  min-height: calc(var(--body-line-height) + var(--caption-line-height));
}

.lh-perf-hint__summary .lh-toggle-arrow {
  margin-top: calc((var(--subheader-line-height) - 12px) / 2);
}

.lh-perf-hint__summary .lh-debug {
  width: calc(100% - var(--expandable-indent));
  margin: 0 var(--expandable-indent);
}

.lh-perf-hint__title {
  font-size: var(--body-font-size);
  flex: 10;
}

.lh-perf-hint__sparkline {
  flex: 0 0 50%;
  margin-top: calc((var(--body-line-height) - var(--lh-sparkline-height)) / 2);
}

.lh-perf-hint__sparkline .lh-sparkline {
  width: 100%;
  float: right;
  margin: 0;
}

.lh-perf-hint__stats {
  text-align: right;
  flex: 0 0 var(--lh-audit-score-width);
}

.lh-perf-hint__primary-stat {
  font-size: var(--body-font-size);
  line-height: var(--body-line-height);
}

.lh-perf-hint__secondary-stat {
  font-size: var(--caption-font-size);
  line-height: var(--caption-line-height);
}

.lh-perf-hint__description {
  color: var(--secondary-text-color);
  margin-top: calc(var(--default-padding) / 2);
}

.lh-perf-hint--pass .lh-perf-hint__stats {
  color: var(--pass-color);
}

.lh-perf-hint--pass .lh-sparkline__bar {
  background: var(--pass-color);
}

.lh-perf-hint--average .lh-sparkline__bar {
  background: var(--average-color);
}

.lh-perf-hint--average .lh-perf-hint__stats {
  color: var(--average-color);
}

.lh-perf-hint--fail .lh-sparkline__bar {
  background: var(--fail-color);
}

.lh-perf-hint--fail .lh-perf-hint__stats {
  color: var(--fail-color);
}

/* Filmstrip */

.lh-filmstrip {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  padding-bottom: var(--default-padding);
}

.lh-filmstrip__frame {
  text-align: right;
  position: relative;
}

.lh-filmstrip__timestamp {
  margin-bottom: calc(0.5 * var(--caption-line-height));
  font-size: var(--caption-font-size);
  line-height: var(--caption-line-height);
  padding-top: 1px;
  padding-right: 6px;
}

.lh-filmstrip__timestamp::before {
  content: '';
  height: 7px;
  width: 2px;
  background: var(--metric-timeline-rule-color);
  position: absolute;
  right: 0;
  top: -2px;
}

.lh-filmstrip__thumbnail {
  border: 1px solid var(--report-secondary-border-color);
  max-height: 100px;
  max-width: 60px;
}

/* Sparkline */

.lh-sparkline {
  margin: 5px;
  height: var(--lh-sparkline-height);
  width: 100%;
}

.lh-sparkline--thin {
  height: calc(var(--lh-sparkline-height) / 2);
}

.lh-sparkline__bar {
  background: var(--warning-color);
  height: 100%;
  float: right;
  position: relative;
}

/* correlate metric end location with sparkline */
.lh-timeline-metric:hover .lh-sparkline__bar::after {
  content: '';
  height: 100vh;
  width: 2px;
  background: inherit;
  position: absolute;
  right: 0;
  bottom: 0;
  opacity: 0;
  animation: fadeIn 150ms;
  animation-fill-mode: forwards;
}

/* Audit */

.lh-audit {
  margin-bottom: var(--lh-audit-vpadding);
  padding-top: var(--lh-audit-vpadding);
  border-top: 1px solid var(--report-secondary-border-color);
}

.lh-audit:last-of-type {
  border-bottom: none;
}

.lh-audit > .lh-score {
  font-size: var(--body-font-size);
}

.lh-audit .lh-debug {
  margin-left: var(--expandable-indent);
  margin-right: var(--lh-audit-score-width);
}

/* Audit Group */

.lh-audit-group {
  padding-top: var(--lh-audit-group-vpadding);
  border-top: 1px solid var(--report-secondary-border-color);
  padding-left: var(--expandable-indent);
}

.lh-audit-group__header {
  font-size: var(--subheader-font-size);
  line-height: var(--subheader-line-height);
}

.lh-audit-group__summary {
  display: flex;
  align-items: center;
  margin-bottom: var(--lh-audit-group-vpadding);
  margin-left: calc(0px - var(--expandable-indent));
}

.lh-audit-group__summary .lh-toggle-arrow {
  margin-top: calc((var(--subheader-line-height) - 12px) / 2);
}

.lh-audit-group__description {
  font-size: var(--body-font-size);
  color: var(--secondary-text-color);
  margin-top: calc(0px - var(--lh-audit-group-vpadding));
  margin-bottom: var(--lh-audit-group-vpadding);
  line-height: var(--body-line-height);
}


.lh-debug {
  font-size: var(--caption-font-size);
  line-height: var(--caption-line-height);
  color: var(--fail-color);
  margin-top: 3px;
}

.lh-debug::before {
  display: none;
  content: '';
  background: url('data:image/svg+xml;utf8,<svg width="24" height="24" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><title>warn</title><path d="M0 0h24v24H0z" fill="none"/><path d="M1 21h22L12 2 1 21zm12-3h-2v-2h2v2zm0-4h-2v-4h2v4z" fill="hsl(40, 100%, 50%)"/></svg>') no-repeat 50% 50%;
  background-size: contain;
  width: 20px;
  height: 20px;
  position: relative;
  margin-right: calc(var(--default-padding) / 2);
  top: 5px;
}


/* Report */

.lh-container {
  display: flex;
  max-width: var(--report-content-width);
  word-wrap: break-word;
  margin: 0 auto;
}

.lh-report {
  margin-left: var(--report-menu-width);
  background-color: #fff;
  padding-top: var(--report-header-height);
}
@media screen {
  .lh-report {
    width: var(--report-width);
  }
}

.lh-exception {
  font-size: large;
}

.lh-text {
  white-space: nowrap;
}

.lh-code {
  white-space: normal;
  margin-top: 0;
}

.lh-run-warnings {
  font-size: var(--body-font-size);
  margin: var(--section-padding);
  padding: var(--section-padding);
  background-color: hsla(40, 100%, 91%, 1);
  color: var(--secondary-text-color);
}
.lh-run-warnings li {
  margin-bottom: calc(var(--header-line-height) / 2);
}
.lh-run-warnings::before {
  display: inline-block;
}

.lh-scores-header {
  display: flex;
  justify-content: center;
  overflow-x: hidden;
  padding: var(--section-padding);
  border-bottom: 1px solid var(--report-border-color);
}
.lh-scores-header__solo {
  padding: 0;
  border: 0;
}

.lh-categories {
  width: 100%;
  overflow: hidden;
}

.lh-category {
  padding: var(--section-padding);
  border-top: 1px solid var(--report-border-color);
}

/* section hash link jump should preserve fixed header
   https://css-tricks.com/hash-tag-links-padding/
*/
.lh-category > .lh-permalink {
  margin-top: calc((var(--report-header-height) + var(--default-padding)) * -1);
  padding-bottom: calc(var(--report-header-height) + var(--default-padding));
  display: block;
  visibility: hidden;
}

.lh-category:first-of-type {
  border: none;
}

.lh-category > .lh-score {
  font-size: var(--header-font-size);
  padding-bottom: var(--lh-section-vpadding);
}

.lh-category > .lh-score .lh-score__value,
.lh-category > .lh-score .lh-score__gauge .lh-gauge__label {
  display: none;
}

.lh-category .lh-score__gauge {
  margin-left: var(--section-indent);
  flex-basis: var(--circle-size);
  flex-shrink: 0;
}

.lh-category .lh-score__gauge .lh-gauge {
  --circle-size: calc(2.5 * var(--header-font-size));
}

/* Category snippet shouldnt have pointer cursor. */
.lh-category > .lh-score .lh-score__snippet {
  cursor: initial;
}

.lh-category > .lh-score .lh-score__title {
  font-size: var(--header-font-size);
  line-height: var(--header-line-height);
}

.lh-passed-audits[open] summary.lh-passed-audits-summary {
  margin-bottom: calc(var(--default-padding) * 2);
}

summary.lh-passed-audits-summary {
  margin: calc(var(--default-padding) * 2) var(--default-padding);
  margin-left: var(--default-padding);
  margin-bottom: 0;
  font-size: 15px;
  display: flex;
  align-items: center;
}

#lh-log {
  position: fixed;
  background-color: #323232;
  color: #fff;
  min-height: 48px;
  min-width: 288px;
  padding: 16px 24px;
  box-shadow: 0 2px 5px 0 rgba(0, 0, 0, 0.26);
  border-radius: 2px;
  margin: 12px;
  font-size: 14px;
  cursor: default;
  transition: transform 0.3s, opacity 0.3s;
  transform: translateY(100px);
  opacity: 0;
  -webkit-font-smoothing: antialiased;
  bottom: 0;
  left: 0;
  z-index: 3;
}

#lh-log.show {
  opacity: 1;
  transform: translateY(0);
}

/* 964 fits the min-width of the filmstrip */
@media screen and (max-width: 964px) {
  .lh-report {
    margin-left: 0;
    width: 100%;
    min-width: 400px;
  }
}

@media print {
  body {
    -webkit-print-color-adjust: exact; /* print background colors */
  }
  .lh-container {
    display: block;
  }
  .lh-report {
    margin-left: 0;
    padding-top: 0;
  }
  .lh-categories {
    margin-top: 0;
  }
}

.lh-table {
  --image-preview-size: 24px;
  border: 1px solid var(--report-secondary-border-color);
  border-collapse: collapse;
  width: 100%;

  --url-col-max-width: 450px;
}

.lh-table thead {
  background: var(--lh-table-header-bg);
}

.lh-table tbody tr:nth-child(even) {
  background-color: var(--lh-table-higlight-bg);
}

.lh-table th,
.lh-table td {
  padding: 8px 6px;
}

.lh-table-column--text {
  text-align: right;
}

.lh-table-column--thumbnail {
  width: calc(var(--image-preview-size) * 2);
}

.lh-table-column--url {
  text-align: left;
  min-width: 250px;
  white-space: nowrap;
  max-width: var(--url-col-max-width);
}

.lh-table-column--code {
  max-width: var(--url-col-max-width);
}

.lh-text__url {
  overflow: hidden;
  text-overflow: ellipsis;
}

.lh-text__url:hover {
  text-decoration: underline dotted #999;
  text-decoration-skip-ink: auto;
}

.lh-text__url > .lh-text, .lh-text__url-host {
  display: inline;
}

.lh-text__url-host {
  margin-left: calc(var(--body-font-size) / 2);
  opacity: 0.6;
  font-size: 90%
}

.lh-thumbnail {
  height: var(--image-preview-size);
  width: var(--image-preview-size);
  object-fit: contain;
}

/*# sourceURL=report.styles.css */
</style>
</head>
<body class="lh-root lh-vars">
  <noscript>Lighthouse report requires JavaScript. Please enable.</noscript>
  <div hidden=""><!-- Lighthouse run warnings -->
<template id="tmpl-lh-run-warnings">
  <div class="lh-run-warnings lh-debug">
    <strong>There were issues affecting this run of Lighthouse:</strong>
    <ul></ul>
  </div>
</template>

<!-- Lighthouse category score -->
<template id="tmpl-lh-category-score">
  <div class="lh-score">
    <div class="lh-score__value"><!-- fill me --></div>
    <div class="lh-score__gauge"></div>
    <div class="lh-score__header">
      <div class="lh-score__snippet">
        <span class="lh-score__title"><!-- fill me --></span>
      </div>
      <div class="lh-score__description"><!-- fill me --></div>
    </div>
  </div>
</template>

<!-- Lighthouse audit score -->
<template id="tmpl-lh-audit-score">
  <div class="lh-score">
    <div class="lh-score__value"><!-- fill me --></div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --></div>
    </details>
  </div>
</template>

<!-- Lighthouse timeline metric -->
<template id="tmpl-lh-timeline-metric">
  <div class="lh-timeline-metric">
    <div class="lh-timeline-metric__sparkline">
      <div class="lh-sparkline__bar"></div>
    </div>
    <div class="lh-timeline-metric__header">
      <div class="lh-timeline-metric__value"><!-- fill me --></div>
      <details class="lh-timeline-metric__details lh-expandable-details">
        <summary class="lh-timeline-metric__summary lh-expandable-details__summary">
          <span class="lh-timeline-metric__title"><!-- fill me --></span>
          <div class="lh-toggle-arrow" title="See audits"></div>
        </summary>
        <div class="lh-timeline-metric__description"><!-- fill me --></div>
      </details>
    </div>
  </div>
</template>

<!-- Lighthouse left nav -->
<template id="tmpl-lh-leftnav">
  <style>
    .lh-leftnav {
      width: var(--report-menu-width);
      border-right: 1px solid var(--report-border-color);
      position: fixed;
      height: 100%;
      background: #fff;
      will-change: transform; /* prevent excessive paints */
      z-index: 2;
    }
    .lh-leftnav__item {
      padding: var(--navitem-vpadding) var(--navitem-hpadding);
      color: var(--secondary-text-color);
      font-size: var(--navitem-font-size);
      line-height: var(--navitem-line-height);
      display: flex;
      justify-content: space-between;
      text-decoration: none;
      color: inherit;
    }
    .leftnav-item__score {
      background: transparent;
    }
    .leftnav-item__score::after {
      content: '';
    }
    .leftnav-item__score.lh-score__value--pass {
      color: var(--pass-color);
    }
    .leftnav-item__score.lh-score__value--average {
      color: var(--average-color);
    }
    .leftnav-item__score.lh-score__value--fail {
      color: var(--fail-color);
    }
    .leftnav__header {
      padding: 0 20px;
      margin-bottom: var(--navitem-vpadding);
      height: 115px;
      font-size: 18px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAZoAAADeCAYAAAAEuMatAABPH0lEQVR4Ae3dBZyk1ZX38d+59z5PSfv0uMPg7iQB4oRkIbrZbGSz7Js368mbrLtE1903nuzGVuIGgQgxCBbIAAPjru1d8sg9b091fxhBMsN0T1V13+/ncz5VNRaFP+ee89zi8QRBEARBEARBEARBEARBIARB0BTZuru7Be0HOoFYlcirAqgIiaoMGKtbAaWNBYFkD9/JzAuC4H3/57KeZKB0Wb/jea9YVrowFbNC0KVAj4Cr50olzTACCKCy11j/QLG/tlmEb5bXp18GdtFmgkDSy3lS7qxzLKsWzSfVcWCMIAiOzxfvuIZV3S+lp/hSUk5DYSzzCIcIkORKJcsQDqOg3gBgUj8qyP8YlU8DnyEI2oTsfc4ynkjvm65eaJ9z8cuMdQvwmoCpgAwiOlH2AERDCONABZUxICUIgob6R7/ynOz7D/+yjlRuEE8BryAccixBczQBUXCj+Xc73difhcAJ2oFUn1PmcV19dnfxZ1/yM2CXkucJIEeWGsCD1IAKSBUvIyCDGD0AphFEUz9fb9QcEATZvetPSd/7uT/2ef56CpFgDIecYNBMUSOAYES+YJ37XeA+WlQQyN6Xr+bxzP+XX3upJEPPIPdVnpwB5LBXEBQa5UHGgFGQUXIzBDIETFakg6B1IGMWCILq337+NfnajX8lxcISjDBl2oPmcCIMl7fXfh/4R1pQEMjwhX0cLfq5a1eUXn3lGxgZtSCeE2MeLcEAOZABOaIJyDAwAAxh4iFERqaCaQzrhwGlxQWBfv3+qP4/t/xZVo9+RZxhykkJGgCNDEZ4rxV5C1ChtQSho1nO0fr/6NWvMPN6Lif3dWaGABzVCZmpSoAaUMdSRRgGBkEGcbof0RGgAlIBMoKgSe5ev6KcRoVC18Z1C0758Hve7p39SZwBOMlBc4hFPmeM3AgM0iKCwEmqHK7nRef1miXzz6JST5k5etir50gCFIAiOX3AUkBAIUUQqaIyBhMlOlGMAIMoQzg9gGUMJQFSQDlOQbB7sLsDm5f/4+tXdW7b1rM0sqxQdInAotTbRV+9/8z+pEp3LnQV8aU/tz+39PSC70kkotly9MWo/9SY6XtNWIVuFYFsePHZHG78rTc+/fxz6jdQI6U1CWAOKwV8o+RgSRUYRhhBGUAZQnQIzBCqw+BrIYACgA994+m9Y2OF00yUnXLHnlWrvn3XmhVdsEpFVwBLKnWzMMuwIkxSEIFyQfEiGFL+2Pw6L+E/qVFGEYCmdjQABWrcaZ73wG8W/uPm3fPjnRbdirLJCI+IMAgoJ1EQyIpfyJnCaZ25fOqtf/36nrR6FpiE9iOPE0QeSBBJUFJEx0GGEBkE9qN+GBgDxhEZAZRgVvnSHWeVXSlddd8jq9d89vbzzi0V9FxVOXvTvu4VWUqXCOWCgUIBlENElMejQBXhzfLX/LK8m+qhkGmJoBGUAhU+ZH6Pf+U36aChKjAK7BR4QIW1ueUhYKsxbAH2MUOCQC55hTKFC/vW9r3/Tz76C4wXSoBn9pAnKIOQg1SBg1UBHQUZRBgAOYD3gwg1aFRK0NLW7Z7fsXt/39L33HTVeXGUP21guPviezb2L7OWJc7SFztAaYic8lRUEJ4nX+Ov5KcxeDIcQMsEDYAhx+L5Q/cRviYvpIjyBKoi7B4fZHNW415V+a6HtcBuYIBpEASy6gplCl/9t387/7SF219LEtWZO44MHhAmKQ2SIkxtwukoMAIyBAwjcgCfDwFZo0664LaHTu/64t1nnke9+MzP337uBanlTIFzvacIYA0UI0WZHhlCHwO817yMNTxEjRJAywUNQEyNHXIab7Zf4YD0EaE8EWMBYQqKss5Y1lq4R+EbKfJDYATwBMFxcvNW8ah0xK5iIcrcolMFkPMYKih9QD9gaNAcyFFyRGogI8AwRgbI/QDCKDCKyBAwzrQJ/ufWS1099pd86juXPX3z7r6nZXn89OFxWWYNrqOoOB5LmT4Z8Fp5L2ewlgqdtLKEIqv0QV6tf8/fyR8R8cR8zuEEOMvnnJXCjwO5ovtR7rQi30G402V8BxgjCI6BXH6DAvCMNevkz3//Yz8fj8kKkJTgyQjA46xoWwBEEqAO1EArIMPAIEYOkPv9wDhQmXr1BE/qextWnvuhW64+f/POeS9Yv2PeVRksLxcoOwMIGFFOhgThNDbwPvNiuhgmwwG0bEcDYMmoSwe/aG9ho5xKAWUaeOPZauCutCZf3rOOO1S4H1CC4HHIolUKwOtf84P+v/iNj7+RkVInkBNM53Hc4T+mIBXQcZAxiMeBySCSxkzoAFADkkbNQVv29/R84JZrTt+8e97131q79PkYLoosncZA7JRmUIQa8LvyB/y0/DPjdAK0fNCA0MEwn7Rv4S/MuyijTBcVEEAMVRV+oMLtqvIZ4F5gkCCYIhf8uALwyivvOeMPbvyv11MpekCZSYE5VCqAAh5BQXJgMnxERlAdBIanPg+hfgDVFPDMIg9tX1z87D1nPfPOh8684f7Ni5/rvZwLUC4orSBBWM5OPmReSB8HyHBtEjQQkTDAYt4U3cxOlhChzLBHVLnVeG4e7JObgRGCOc2NlGm48fnfWUg9ioAaMy3wUwUIj1IABOgCelA1gAFyIJ0skyCMggwh/gCqEyUjj86FoEKb+M7Dqwp/d8fVz9r24MIbSAo/tmsgXl0uYouRAkoryYBnyK0sZCdVOmgnGRGL2cIl+nU2y2uImHGni3A6lp/vqOpWb/nynsXyhTp8ExgimHPcvnk0dEWVhSCeoNl0qjyHSKNUC0AR6AFdgWJABEhAqqBVvKsiZnJF2+T7yQr70KgC1BBt+rU9P9i+oPjNe8666LaHlr30we2LXpqmnB1FIAK9nUorUoQIz/Pkc4DQbhQhw/Ec/2m+Yn8SxSAoM02BOGEl8HOnbNSf8ykbxg9wi4p8TOD7wDhzQuCWfRdWnlkR63QB4AlakR56fVyCahnoQFIBBAAPmBRE6iBjiB/BuxGIRoAhxA+QR/ungigDUmbIr9/03FOHHu77iVsfWPby2HIlQCGCUlFpdSmwWrazhnVkRLSjjIg1ej+djDBML5aTQ4WGXIAiazpXsgb05wTuxvNFKcgnpcBawDNrBXL5jcrPveBrpTdee/P/Y7wYFgFmJzlsJmSYlCPkqOSIVEGGER3EuwF8NAwMoYxQYBio8xR8/BsXlbfumn/DR799/ktG6/bFkdJdLihKe6kgvEBu5m/lddQoAgLQNjMaAINHEd7t3sPNcgNFlJYg1FX4qop8PEr57Oyc5wTOD0BhWHuBCFBmo0CBfLKERykCWFS7QHtQVkNisIkH6igJSp2IKsgAogOo3U9eGAYqCOPAKEf59HfPP+O9X73iVQ9unPdTKGd2laA7VgCU9mOg8dyMJQOEduQxdDDKGl3LFxtB0yKUgijXC3q9wmbj+S9V+ShwL7NG4Mgh7ZBefAiaNjQDt2jLoQCCMjllMuYBy0EEvEGq+VTQVIARjB1Mk6jy/YdPWfr7n7/2RYPbup9jnfbP68ypp5YkAxHBCIiAESaJIrQ2RXDASjbgsbQzwVPWYQytyRtW55bfENU3E3MzVt6rwteAUYK25rIesOQ9gANSggB0qiYJRxOMdwhd1Wph2cM7F527bseiC/YNdS99zXn34s8Xxusx47UCo9UiY7WDFTNaKTJUKTFWLZB7g5+ozINXEMAYpoJIaSUGWC5byLG0s5SYFWygm4wEh0VpNaIAFKnzYtCJ4h6FD8WpfBTYR9CWXDQEL7/qni6qBfukQRMEAhifgeZDo539D25dcvEjuxZfPBEgfaA46/EIAnQV6/SUapj+IUDJvWlU5i311DbCZqRSYvhg8NQKVA4G00SNVYtU6hGqNCiThEPdkIgy01KEjEkCdDLMyaAzfHzWowcQlCpgESLAoTwV3gtJDtZAZJVpJTQIXHywfKS/Jrl8RHM+DKwjaCtyyQuV7/7du14ex/kVQJ2jBYGgGJ+j6IGhrkVrty29aP2uhReN1wpdzipGPD+KAIgCIAKCYmSyEEgyO1GOWhJRT10jfIbGywxO1ESQUU0d9SSi2vh5g+pU6BxeAJx4ECUI8xnkeXyOpbINUF4qH6OL4RntanJVMq/MFEPOKPO41byCGmU2s4Zv6I8xQgcRyvHIvFBwGacu2sS+4QXsHemd+VsbBIADAh8zKv8KrCVoC/K6X97p3vuWD766GKVnAylBcDibZ6joroG+ZfdvXnbl5j3zz03SqGBNjjHK9DgUPiL66PsGARTqWcR4bbLrqUzUwSAaHi9PVImRarERTlluSHNLltMgAuY4u6AEYTWb+DPzc5zH9/E4QKhRQhFmmjBzFMHgialiUIScb3Mtv+3/hSH6j7mz8SqU4grv+Mm38dwLb2HrvlX84cf/mLs2nk/BKSfJuCqfVZW/B75H0NLkNW/a2fH+t3zotUVXXwmSEwQA1mcounugZ8n9m5dfuWnPgguT1EXOekSUk01EMVMloiiC9wfL4FWoJlFjHjRSKTJaK07OhyZq4nPjOC7NLKrgG3XUUZxRBFCEFOWP5Dd5lfwb4/Qx23UwxN/r2/lnfQsllGNRqQsvvuwW/vINb4U8gtIoX/r2T/LWD7yTcgFAOYkyVfkE8A/A7QQtyWW5iVHKIEoAhIBBNN83ETD3bFz19C17+8+vp67gjCdyOc2iKuQHiyMJYIzSWazTXaqxfP5kGOVeGt1NmrmJspMdUKV0MHgar9WDnVESUZnqkNIccqBb6pxu7ieVInAokWYrT8xF8j1U38KxEgOj1S7II3AJoAxXulGawono64BXCHxCkb8FfkDQUuR3fmv9oj964yd/puDSMqDMTYFRj/Hp0Ejn/B9sXHHlwzsXX1JLXCma6mDakYgicMRxXONVlCw31NKoETjVg4GTxAxVyoyOxfxK9Te5OPkmtawAaQZpDl7BCFjDbNLBKJ/hdfym/wfKKMdCAVXPG5/3YW648lNs2H42f/6ZX2fX4AKcVZpsTOAjxjQC52GCliB619+eyryR14I65p5AVLF5MjZe7vnBppVXrtu2+NLxetzlrMeIMlsdCqBDCwkopMScyoM8N/8spl4nq+ZQT9BaSj5Sw+8agiwHYQYICDPKyKH/XWPqjNHFm/3HuIOnUUCPq8OsZ1CMlCQTjNAImRYyCLzHO/kbYDdNFYhu/aOLyM0NgGOOCQHj06QeFddtW3reDzYvv3pwrGOBszlGlLlL8Ahnyf2ca+6lJFUQQUUoZGP4u9eh1QREmHbqwecgwkwQYLxeppoUEFF2sZz/0F/kq/pCIkBQjpeqtHTHK45NQzvkr8cH+AAwTlMEolvecTXePwewzClhk2z9jkVn3b1h9bP2DXetEFGs8QQAQoajSIUCdRTwavixp9/N/Pm7IQcQpp/C4B6ojoIYppUo2Ix//tKNfPS7z6cjVoboY5QCRQCU2cpYEOFuQd4BfJrjpB30qNIjUGRSAowCBwiOiejmt12HckUImjkyhxGf7RvsWXz3+tXXbNi94CJVcNYTPJbHoAgAuTe86nnfY9GqPaAWVJl2YiCrw96tkCUgMu1B8+7/eTP/dut1dBXAABZlLokyPm28vAu4kyfgu+jP+rjCC9dV53GONSxVZZ4IJSbVUYaBnSiPqHKLV24DdhI8LgdSBhWC2UsAmyfVaqF8z4aVz3pg67Kn1ZKo7GyOGJ5AYPAcouA9ZB48M8SDRFDug4HdIExv0KhifUYMRChzURLxMtDnCfKP3vCXwABTagu4uL6AnykrL1FhNYA9+iraQxYBZwDPFvhZa9iP50uqfBC4leBxg4bZLTwPs2H74jPvePjU5+8f6Vwa2ZzI5bSiQKHcA2NDkNRAhGB68xboAv0d43mJyeV3h5awTubzK7HwUx05HQoIx0mZj/B6EV4twmeBdwL3EjQ4lCIgBLNx2J8MT6wr377u1Gdt2LXgYo+Y2GW0sEAVrJ0Mm6QKCDMgUMBzbjqPTxfnMaDQjwflhEUKP64511W28Bfe86dAEoJGNEYJZhPjM/XG3Ld+9ZV3r1/17PFa3OOsx4knaJOwKXXAqIN82rfQAgUMZIuFvB9B6UeZPgpi6Ow6g7chXK7KzwK753jQMMuCJnQxBwa7F333oTXXbtk7/xwjvh2PyULQRAVwMeRVgukPmXQZ+D4gZ8b4FARu8I7Pbt3OK4GtzFEOJAYlaP9ZjM+NTHQxT7vnkVXPHU/izsjmBG0sLkK9AgjBNBHIlgq+F8hPUq55Ll9R5n+yUW4A9jAHORQHCG0tPHg5ONzV/50HTnvBxj0LznPG0+4hEwi4AiggBNPBQ7ZEyOcBOSeNerC9XObm8T6ElwEZc4wDNQTtyfgcFX1w87KLvrduzbXj1UJvGPbPEgJYByjBNPDgeyCfD3hOOvWNul7ht4B3Mcc4wBC0H5cnlWqh4ztrz3jBup2LLjNomMXMNiKNOkGBAhFkiwQE8DSNgd/0yufn2g3TDhFBlaBNiHpsnm7dvXDNtx847cf2j3QueZIbloMgUMjmgZaAnKZS6Eb4A+CVzCFhPtNOrM99buWuB0951l0bVj0nz20cu5xgFlLA+xOd0QQKWgDfJ+BpCQIvF8MzgW8yRzi8KiC0tsBlyeh4ufub9591/cbd88+LrMfZnGAWy1NOTCAKebegMa0UNCaHX8wM95cMw4CfC0dnHlVDSwvPxmzbveDU2x444/qBkY4lc6GLCRTSOgjBU6WgFnwXLUUB4/mJ2PNMEWoC6wVuQ7kF+C6zkAP1tKbAaK6ov/fh1U+fuKfsusybeI4M/AP1kNQAIXjqNAZfAjytxgJLMwWFU4EXAG+zwje85W+AzzGLOIQcpQWFBzBr9Tj+9trTrntw29IrrPU445kDAjFQG4P8hL4qINCpkLGAp2UJjzJeeY5mPAflw1h+HdjHLOBAUtBwsWYribL64GD3gq/df9ZLdg70rpljXUwgQHUMcg/G8AQCzyHCIXroVUtCuxEA4adRzspyXgVsoc050DrQRcsI85ituxas+fp9Z71spFrqD0/4zzEikNahMgJGCB6HBwxoGXwn+JKgEQ2iQB1MVbEjoBHtS7kisnwmHeF6YAdtzKEkBK0RMqLZ2k0rLv3W2tNfnHsTz8WQCQRGDkCeghiCo3jwXZD3C74TMBxBATrAi5AnoAJ42pfhQp/wntoOXgYk7dzRJDRXYHyuKnz3gdOfc+/Glc8VVKzxzDGBMVAZhfFhQDhMoIBAtkjIFwAG8I16QuoApa1pDoWFvKi0hJ8F/ok25RBTQb0CQnDy2TxLkjj6+n1n3vDwzsWXOBOe8p+TxEBah6E9oAoiBEeFzFIhnwco4PnRlFlBc8hzfgvhk8C+dn1gswIoQTNCJh2vljq/es85r9i6r/+MyOUISvMEXs0T/7gIGAGEaSUCSQ0GdkKegDVMOwGMoGLIgRzhaAYQlJajU7cu9wM5c9UK8bwC+DfakEO0gtIE4VLM/YM9C2/9wdmv3DvUtaz5ty4HRjwFk/B4cjFInkEtA2+YPgK1MRjci9brIMcwVJCncDONKNiMOB2nm1E6UQ5RFKFGGY9tzVuX+wHPnKbCq9s3aKwbJ8sITiKX1Xbt61/51XvPeeVIpbSg+evLQeojTu3cwrVLv0nuHQACIAKAihDtSknv2AtpBiJMH0VrCdkdD0Oag/Ckqt6TAsLxe3n9d3mReRuS8ShLTpUyb7cf4CE5nwilZRjI5wtICBrgfIFlwI42DJp0hEyU4OSIstq2ifXlm+8991XVetzd3PvKAhFFAGs8TnIilxIhAKgCuQfvIVd8LYPUQy4gTB9jIFG0kkGW/8gQ0zTDe0U4fmWp0SEKemTQVOjAkaAt2M34MuAJoFuFs9oyaP7s6y8e+ZUrv5LHJo0AZeYELq9v3Lb43FvuO+fHk8yWQsic1AfgAMXIZIkoAGnuqGeWSlZmODHQMUYuRUgydKLIPZr7Q4EjAobpZQSt1EEVjAHhyRnhqfJYHkvIcShCSxHIOwED5AQQAYtpQ+62HSuSt6jUgRKgBDMWMg9tWX7xN+4/4yW5N4Vwncz0E0DMkUHiveD1YBnSzDFSLTI6UePVmNFakZFKkbFagX3VLq5KDvATV27Gz18GWU6DMEVAhBkhgg6NQZaDs0wJDGhJwDMlUKVIG3IlmyagM3p7X3jaP68/sGnFZd/44ZkvQ8WGZ2ROIEhEpwoE5VECWW4Yqxao1GOqScxItcBwpcToeInhaolqPSLNLVluJkoeveHFCFQF8B72DcHC5WCEk0IEkhS/fxiMcJhAAMdhAoE6bcgZpA4yDgjB9BIU45O1G1de/s0fnvFSBGueNGQCEQA9LFR4tEPJvVBPo4ly1DPXCJShgyEyXn60M6klEbXUkUxUmoMRkEPVIICzekTzYBAwAjsH0NU1pFQA75lx1uB3DaDDVTCGKYGCGlDhkCATwx7akJNIEzSvAIZgehmf3rd+1dO//eDpP4aoNaIcEkwFCOZgGcWrkOV2srw5GBqNIBmplBrHXaO1AuMTVanFjNdjkswggB7R8RyqQqTHP5Sv1sk37sadtwoEUGaOEbSekm/YxWMF4kEAJUBAc4aTAzxAG3J33r9UudZVcLkhmM7LMev3r1/59G89ePr1ImrmYMgc6kamCkBVUAWvQiWJGKsWGas3AmSi4smjrkZ3UqSWOLwKuRe8BwWMHOpSIqtMO2PwW/fh+7swy/ohzZkxIuTrd6JDFXCGwwQCKJADjkBAPWtdDztoQ871wKc3Xjj66gtvU5ICJygQYGom860HTn+xiIoRneUzE4DJV+HQ5zS3jNViKvVCIzTGapMzk6GxcmMoX6nHjV+TZpYkE1TBmENBIgCiWHOwTmI6eiX/4VYoxpj+rukPGxFwQr5xD37THp7gP1zgQaqgRUDDkXJ9Fx+nTbn6Ltj5YHGIyzUlOeFONbB5/cGpwT+CGNFZtBoMcth6cJabRkjUs4gks42OZGi8fLAaQVKtxxMVUUliaqnF50fNSmSqgNgpLcPI5AOUd2/AXXQKZn4P5B5UOWFTKZpv2E3+4DYahODxKJhRxfdJyFzYVjX8D23KVQ2YNX6ElAxwIWhO7AvL1m1efuFEyLwUsEa0PWcmRhEUr2bq2MqQedvoQEarxcbcZOJ1alZSaAziD75muQCgOlkcdszljIKhfdjJeU1253rsmcuxKxeAtZDnPCUiYA1aT/HrtpNv2QcCiPAEAgN2DPIaaBHwzFmJ5y86lrOXNuU6lkOn+CGYCpqnLDzxv2nH4rO+PhEyCq4FQ+bILS4UAAUEIVeoJVEjMMarxcaR13C12JiXTA3jSb0hb6wGG3IPHD4zMYo1yqxiDGQ5+Q83o/uGsWuWIH2dYAAPqAfliclhSZvl+O37G52MDo+BtRyDIAV3QEmXC3ORCkSGr3QY3kMbc/McfHn9paOvPueu8c64WsIbguPksmT77vmn3nLv2a/Mc1O0xrfMarCgGFEUoZ5Z6knUCJTqRI1MBcnkcVeJetZYC278fJo/9u+VwiTTCBXmBpFG+d2D+P0jmAU9mGXzkJ4OpBhDZEAB1aN+D5Bk6HiC7h/B7ziAHxoD5XhCJrBgBsB2QN4H5MwdBiTlIfH8dAI12phLKvBIpS9PE7ePAguBnOMSrvrfvb9/2c33nPeqehp1nKxrZUSOnJmAkuWWqQcSG6ExVi0wWikx2JiZFKgmcWNuMvm8iUUfM9g/9HrUzCSwBrzH7xpolJQLSFcJKRehFCOxo0EVradotY6OTdRoBerpVGIbMARPgdulqBN8F5Az+1mQcYh2aJlElgF7aWNO1tNQNPk+wAIpwTGHzPBoZ9/BTqZSj3uczWfkKXgjCnJoNVhVSHLbWAkeO1jVIsOVIqPVwkQVD1YjVLyXRuUKqiACZqqcVYKnMmcRALSaoON1GgwgQoMCKPjD/gt3lhMQCJBBtFVJlwq+F9BGzT4GUDAD4HYrkrIS0f8GuRbY2L5B42lYu/b0PZc9424lNxyDwPqsXi8Uv3rv2T8+0TEsjI4zZARAjlwJFhQEBMi8aWxs1dJoagg/GSgjjWF8ufF5qoMhzQzZYU/BGwMCMDXYNwTTbSqxn3hNzxBMJwFyiLYr+biQ94MWOURpX8IkDzIG9gDYEaXBAHCqop/0yHXAAdqQy4WG/3rw9AOXPev2cepRDHieWGDU+8zYiZB5xc6B3tWxy580TI5+eNFMXaeSZo4ks40aqxcad3KN1A52JxOv40VqU9etVBtPwYPIVHHke2OUgiEIZjehwR5Q7DD4TvBdgi8CBlRAaDMeJAVTBRnVxiseMBxB4FKDfsyovAyo0GacUxpKqe73uR01sOBJgiYQnYD/+v1n3rBx98JzYpcBIKJHBIki5I3trIMlVJP40WtURiuNMGmsB1eSyZlJNXGgNCgcCieOuE4lCAID5GCGwAwrCKgFDO1FQXLAA8ok06jHJXCtyfWfXcYbAE8bcXFdAfjy7efVX3vdyr1nrN6+iCTiMQJB1OCy2n0Pn3rV+p2LrywXEqZQSx3j1UIjOMZrcePZkpFqibHGVfSFxtPxuZep4AFVMHLYMb5RjlEQBDJVUySjPcmhOhaZ48aJ2gC8gzbiakUeFTu/Gbhgzv9fVxFQAcyhH9c6pfruu3549iWfvf3C68brMaNTYTI8PvnAYpJaktyRpIbcHxkkIjSIKJGlBQUGD9SJKfB4shxUAWFGGQEB9InHgxOlyFN+KJcjWHIyHIKnbQlzgtDwNlFZD3yMNuGMClP4yNev2PIHr/9Uwuy+NFWYZB4twQAZUAcSIptgzSjKAdBBusoH6JAD7/i7Z57xpW+f87bhasEAiDz+avDUFfRBGxGgoh3s4HQqdPAYCj09OZEDVWaMAEkqZDlPqFY2pIBwfERgvOao1CKMKFMw5NQoUaMDIWgDoqLvSXLZCnybNiDn3KBM4fzVO6OP/+E/vpGx4nKElPZ2eJAI4B8tLznoGCoDGB0hZQjPCDCI6DAdpWEg5TB37Ty9+6ff+fJbNOOyMC+ZvQTlaKqQ5cJvvWGQs9ck1BNhpkRWueehIht2uCdZQReeCmeVBzYWeHBDTOR4HErQVjYoPBvYTotzh1+1/tC2JemB8d4t/XZ8Jd7S4g4dbSkCCJMEUESqwDDoOCmjwADIAIYBhnSIROuIJkDO0QarHO7OTSvNL3zs+vdIzmVxCJlZzWM4mgLWgnUCGBBhxhgFDNooZVoJGAMKqADa5qdPwRoR3q/Ii4E6LcwhwuE+e9OlP/yZF996pdStAErzCMBRQWIapQCSAOOI1ihQRWQYZB/4ARIGQSvAOGiVCE+D0tDPcfm/7/6pt2d59Kq5+7R86GjiWImsoqqgzBxVQJGpmk6C4owigKgSzALKtaL6V8CbaGFOvHK4j9125fb/88LbtiF6CirpSR7EW8CACkKGkjZeY6kBQygDCIP06jCiYyhDGB0FasyQt7//xT8+Xo1+p7usKHNRoAjOeVwjaGhbChijiBDMJsIvA3cD76dFOYQj7Bvt8A9tX37XWadsOYV6NF1dzZEdCQqgh90AmYKMgQ6BDONLI8DBGsDoAGUdATLAA5BwUrzjo88/7QP/e+k/9HaqUdpLkgkCRE45QYFC5MA52p41IKJMJ++FegJewVmIoxBmTfCXGLkXuJsW5DDC0f7iw1ev/dff3XxlZHQlXpLj3whXATFTr4KQA1NHWTKOxiMIA6gOYO0A3Z3DoAlQAzJawL++75LyP3/y0g8sXswSlLahCEkGK/r34L1lx8D8E3zYM1DAWW2UqtC2VLAWjIACwolLUqFYUC48c4zOzpRde4us21zGWbBGOTkCEfryTD+wa508Bxigxbgda3mMHWvPSn7r515w8xnLv/jTjJcdQgYIU47qTgyCAlNBIXXUjTVCRMwBvB8kYxiRCqpjwNgRWZLkUBmg1Xzq3vP+on8+V6NKO0kz5bVX/y8/+4J/w6vwL196E//zvRefwG3MgSrEUx2N0r4UsFYRAVVATjxkli+q80e/uJ5nXDIINmdsLOaTX1jKP3xsJV4FI8rMC1TBGC5Yfq7+A/A6Woxbfq7yeF79zms2/O/v3PXF1Wt2v4jUxkA+WeJBKogMgg7hoyHUjQIjiA6jdgCo8yhLu/n5v3rda9bt7PqleZ2KajuFjLC49wC/cO2/M3/eThDPm174L9x83/Op1EoYowTHTxUiB1Gbz2hQsAaMQK6cEK+Cs57ffeNGnnH5fsgsJI7Ocs4bfnIzewciPvDppZRLnFzBa9Nxvg38My3EpeM8oRf//ltv/9Nf+d+9jNpTERlD9AA+HkRdBUiBjFlmy76+0773yLK/6i0rqrQXgdw7kiwGkwNKksZ4b0A4AYFzOlG0PWMUkenoZuC8NVWedsEQeAteaMgEYuGFV+/nEzctIc/lZB+hhc4m5h1JVb4F3EeLcFkuPJlf/8sf3wRsYg5QT4zjX4pllghKu4mssm+kh7/5/Fv55Rf9UyNg/v6Lb2asVghHZyfc0SjOKr7dt86sRYQTHtKoh45yTqHgwXMUoaOUUyp4RsctJ1GgYCzzSt3670bluUCFFuA6ugim5J7fRvT5tLHYKV+4+3nc9tBVqAqj1UJTlwFUBQARbf+gcUo9EdqRGosKdGYDRMwjoYCgJ9DhwZZdRXbvK7B4aRUS4RDPI1vLDAxbirFy8gXqudKj7wbeSgtwXhUIRLka4bdpf41gqdSLyNT7Zq5YR/bQ+3buqiIH1tBmBDUWUOLxAboGNtAxvJWSXs8YBU5E5JSde2Pe8z/L+f1fegSJcyYpe3aXed//rsAaECFoEoU3Gy83AV+kyZx4Ya5TodOL/iNQYpawRpu+mPDMs2/nLTf8Lbka/v7zb+FbD13RnmEjUIg9SpsQwYtF1FMc20PngY2Uhndg8xqIwZkMPCesVFA+/uXFHBiOecXz9tDVnbJpa5kPf3YpD28pU4iVoKmMN/q3InInsJcmcmqZ88aL+q6OCheqMA0Cr0JXqcrvv/JdLFvyCAj89sv+gtf/wwcYrnTirNJOBCjGCtoOAeMwPqU8sp2u/esbQWN8hheLNxEGTyzptKw3i0DklC9/ex5fmag4gmodIkcImRahcHqk+hfAjU1eplHmMoe8IK/ySypMk0CByGV0FschiwDoKIwT2RSl/YhAIVaU1qQiYCwmS+gc3krnwEaKY3tBPdoIGAdTRJRIUqaLyGRnowqqQkdJCVqHACm83iBfAD5Jk7gcYa6q7qdHO/UvSiWmMW8DIzAw1sW/3/xGfunH/hFV4X23/h/2jvYRGdpSK/4TuopBxWKzKh0HNtF5YD1xdRDUo8aBGB5PbFJUpj+MRZSg9SgI6J/1WfkGsIcmcH2WOcsu5I9S5QJVgmm/JRg+/I3X8I0HngkKW/YvI7KKtHNHo7QEFYuKIUrG6BjcQsfAJqLa0KHhvxieiAAFk4ICAhB4FbwHY8CIMtsI4GH1/lz/FPg/NIHbnytz0f7N8rwFp+ibUGZAIALWwMa9yxAgsiAA7Ro0BW2JFWUQotownQObKQ9uJqqPosagxnFslILJmBTkXjAC/V1DDFV6yf3sfcBU4MahnfIZ4NOcZG54pzDXdPTTOREyfw5EzJhARCm42RGahQhQmmIqRIgrA435S3loKy6tomLwNuJ4CBwxowlLK2P81kv+mqed9W1uf/jp/PlnfoXhSs9sDRuZt1L/DOQbwCAnkZu3kjnH57wJ5RKC4JgoxYKiJ3uDzFhEtTHYn1xR3o7N6/ipAf9TFZGiBJU6/NTVn+cl13wU0iIvfuZ/sm7Hmfz7La+ho8Cs5DPOUOG3gd/iJHJ5ztxiOcegv6UEwY+mj3Y0Hj1J8xdvY0RzyiO76dr3CMWx3YetKDtOlCNlUhBFCQigFlAil6DKrCaqb/bCfwPf5yRxijJXjOzDdHbxp1KglyA4RgKNjgZlxqiZDJhiMkDf7g1UNhygo7bniBXl6aE4MiAoxfCZ79/AFWu+z0Vn3M4P7n0hn73reooRs5ooJYG/3LNIrgUSTgK3d6EwVxQjXhlV9cVKEBwjBZGZu8rH2wg1jrhygAWbv8Oy9V+gsm0F++rnoNaAGKaTAFYzILBGOTA6j//3gb+lv3sfB0bmU88cziqzmQoIPHPeADcC7zk5M5oB5oRinT4VfZtaguC4OAvOgSrTRPDWocZRHNnFwo3fYNGGWykObQeTomY1ahyQMt0UsJJjhGAqbNLcsvPAYowBZ5S5opDo74nwOWA3M8wVU2VOsLxVlbMIguOgCnGsWKOATEPARCDSeP5l4fpbWbDpNuLR3WAcuBhEmFmCJcOhKIKghAeMFWOZeyyr6qP8LvD/mGGuPs6sVx2Rs3qW6VtQguC4qApx5DEG9EQCxsWI+sb9Y4sfuZn5W76DrQyCdRCVOFkUsOKxeDIsc1egHlyZ/ytePgjczQxyUVGY7Uq9/F6W0kMQHCcF4miqo1GOi4ppBIzxGT277mPJRMDM2/Z9TG0EXAGiIiefYMmxkpOqRZjLAhHK4vhD4GXMICeO2U24Jkv11TwFQaAKhUgx5ngDpoBLK/RtuYOl675Ez64fIGl1KmBKNIsqOMlxkqEaEwSq+lLgBuDzzBCnqsxahkhy/hjBcYIUQEGEOSRQnepoLOixPAPjYqLaKAs33dY4Iuva8wD4DGzcCJhmUwRnPFY8KCAQBAp/LCq3AhVmgEOF2ao6yMvLffpcPE+ZKtQTwTmInFJPBfXh+zbm1tEZGDmWFeUB5j/y3YmA+Sod+x8B9eBiMI5W4iRvFEEwxSiX1or6U8C/MwNcvajMRuOdUuqp6++gJxYyWS68/Ln7eNWLdtE/r86mbR188H+X8937u8P3oc8FCoVDM5rHX1Ee3cPCTd9k0SO3UBzeCgjYCBBajQKWyaBRDgkCl/Mb1ZJ8Ehhimrk0FmajZQO8rlriIlWesloi3PiSXfzOLz5Cgworlla54txh/t+fns037+qlVFCC2b7e7LEWcn/kinJ5aBuL1t/C/E23URjZBcaBjQGhdQmWvFHKpCBQAZdyWlfK/wX+imnmukaYdayntyb66xiesjwXFs5L+ZmX7gAEEgNTip2TP37H/d14bzBGCWb31pkxkJoCeN+44LKxorz5W7jKAJipFeU2oIAjx5ATBIdTAUHfIiofAfYyjZww+9QtP2XhTE5AlsOKRTX6ulPIhSOosLLxczn7Bg3GEMxSquAKESZy9Gy9n4WPfJX5Ww+uKA+BmxrwtxXBkGPwIATBERRW5OjPA+9gGrkMZTYxnl5n+FUVTogxMDgSUU8MxY4ccg4RZWjMMV41GCGYzSwsGl3H2V/7AMUN9yFp5dCKctvyODIeTxAY4Ze95z3AbqaJQ5lVROQNKnoKJyhyyqadRb7y7QW86sXbwFjwAk4B4dO3LmJ4zFIuKsHspAhxDOft/SKlka+B6W0ETPsTXPg65ycWLDoYNsAfME2cEWYNL9Kj8ItME2fhbz6yEms91z9rH8VSxsBQzEc+s5z/umkxpQKzXTg2M9ARZ+BKoIbZIibjCQWB8EaQfwZ2MQ0cIswWBm4EPW36gkYZqzre9i+n8YFPL6e7K2XfQMyOPQWiSBEhmOWcKJ1RFVSYTSJJEeGJBMFihJ8F3j5NQcOs4A09NtdfUqaXs4pX2LSjiGoRYyCeEyETKOAkp2xq4IXZQoFIwtFZ8ORU9Y058i/APk6Qy5RZwRpepjlnMgOMTIbL3BNYySnNsqABIZYMEZ5QEAisMJbXAH/PCXLG0vb21Ijnj+mb4m5Qz7QIAgUMOUVqgDCbxCYlCJ6MKCj6i3sXynuBCifA7VlI2+sf4kVxlcvUM62CwOIpzLKgUaAgKUHwZFTA5py1bDs/AXyIE+CWbaetqSBi9Jc80y8IDDkFnX0dTWRShCD40bzTX1DkY0DCU+RyR3tTrhR4LtMsCBQQ9UR+tgWNEJERBMdEeRpWnw3cxFPkMEo7k1zeCDhmQBA4UqxPQZhVnKYEwbEynp8/oaAxnrY1ulNWdyzWV4ow7YJAgbJUEfGzbkZjJUNQguBYeOX6eUbOA37IU+B6RWhXbon+dAI9zIAgUKDLVTEos43B4yQnUxcCJ/iRBApDXt8A/CpPgRvySjvKPB3G8JPCzAgCVeiJK4goKLOCqEd8huCxeDKC4Ngo/DiedwCDHCennrZUynhuvcA5KDMiCBTojiogHlRmQcB48qhIre8UtsqZ1IcjBCUIjoUKKwuZ3AB8hOPk4kxoR2msbxRlxgSBBzpdFVBA2jZg0Jw87mS8dxXjfavJu/pIBgyqIEIQHBNRSGJ9AyL/ASjHwSUF2o7COaI8nxkUBKrQYaogSrsRnwNKVuhuhMvYvNVkhS5AcXlGJAYhIgiO09UevRL4HsfBeZR2EyfyijSmLMqMCoKSVAEPWFqfIt4DSlrqY2zeqYz3riCPO2BqNgOgBqwFhDYQqAoAIkqzCTjNedVxB43mtBeRUhbrT4oyo4JAgRLtcHSmiM9BDPWO+Yz1r6HSs4w8KjV+XHzG0Ywo1kDuQQhaVT0VjAHvQUSInTZ/Nd7wciPydmCIY+QiK7QTD89COY8ZFgQKFLUK+JYOGDWOWtcSRvtPo9azhNzEiOaYPOWJiIA1Sp4LCEELSjLhGWfexY3P+RC1pMQ/f+UXeGTXKURWaSphdZZyHfAJjpHLUtqKi/Q1npMjCCKtAdqCA36PGkeldxVj/adS61yEGjsZMD7lR5gKGoIWleXCgu5B/vAn3snKFWtBlN7SCG/8139GVZp6jGYE6jV97XEFTVpT2kWlLIvmwbWcDEEgEOU1UG2ZgBHNyV2RavcyxuafRq3cD2IOHZEdCwURMEYBIWg9uUJXcZwlvbugVgaXsWrBFiKXk+YOoXm8h2I31xRgNbCZY+B6umkfRZ7rKywRZlYQKIIViKUOSEsETBZ1UOld2ehgklLfoeG/ZhwPBYwBawkrzi0qsrDtwGL+5/ZX8MqrPkFWL/CRb76OauKIndJs6unLM7kO+DeOgcsToV10JPqaNAKUGRUECsQCJUlApWkryoKSxl2Mz1vdWFNOit0IiviMEyEyFTQErciIknvHn336N7jl/udRSwrcu/k8Iqu0iiTSVx9z0CSR0g6sl9UKzxBlVlIVVMEYJWg+VShaT9nVOal0MkTMRKWlHsbnncJ43yqyyRXlxo9PB0GxRglalzWKqvCtBy9FBAqR0kpEuRzkHOABfgQnKrSDzPI84+mfrYO/3EMhUqqJUIxaYmc+bJzZlLKtA4YZpx7yFGze2CA7sPAK0r7FZIetKE8nY8AaQAVQgtYkohRjWlWH8bwQeGDWfE2AoC9VZp/MC/O7Bnnri/+O5Qs3cfNdN/Cxb78SmrpZEqhCbNLJjsYLM0chq4MrMLz0Qg6cex2bRq9idE8nkWSYPGUmiIAxoDx1QaBWX6xe/hbwPAnnhZZnhGUqXI3Oxm4GfuY5H+alz/wPyGIuXXUfa7efxZ3rz6cY00xhRmMyimaGgkZzyBKISgysega7z7iWoaUXYYoF/P3SCBixyoxQEAPWKKBND/R6ImQ5GAPFOBwftxNVnqY5pwPr2v5mAF/gOnL6mIVEYGnfLvAOkhKURpnXMYQSND1oJKUgCSBMG59BnuALPQyccs1EwLyA4YVn402EzevYtIpoETAz/MVnYG1zj85yL3gPF505xtLFNUZGHfc+1M14zVCIlLYQFK3R639k0LT6QDDOReqi1ymzlMLHv/NKLjr1Hnq7DvD9e6/jro0XEzmCJlIgIqUgdVABmY6ASck6+tm36ir2nH4tY/PXAGDyFJvVTvrZvzWK0hzeC3Hk+fUbN/Gya/dQLKXgLXf8oJc//MfT2La7SBzCpi0oXBfJkx+fOSdCK6sYXWAyns0sVYiU7667jBv/4QMs6dvND7eeS6VewFklaC5HRsQJdjR5CupJuhaz99RnsWfNsxvPwogqJksApVmMBRGaolqHN7x8F69+yXbILSQODFxx8QF+942GN/3J2WiYU7YHy9N3bNCVwGaegNuxSWll3QvlilKPLvQ5zOaw2bp/KZv2LCWOCCHTAhSwpIgmIBwnfTRgaj0r2HPac9k7ETAHr4kRzRvdSytwTZrR5F7o6fQ8/8r9gEAuNHggt1xx/jCnr6zwwMaOMKdsA6p09S3l6U8aNH1LaWmurNf7nFkvsjpRBM2ioHrYew9RWod8CLQAGBALGECefEUZqCw4g12nP58Dq55GvTz/0PFYi9AmdjSqUIg9pWIOCEdQKERKuehRpU0ErsSLgY/xBJwr0bKMl06vejUzJAjUAwomAhuDLYEpCJGF8bifz5Vfy7xsiFXZVvrzfZT8IGBAYkBoUIW8DjZmdMn57DrzOg6suIIs7sLkSWPA33JUcFYx0pwHEQ8MOR7e0sGpp44Chkc5z/adJbbsLIY5ZTtRno5IHzDI43AgtKrhbs7sGuEMhGkXhIARIOqCeL4Q94DrBAyI0DDEIv5KfwUBYvWsTjdxcf1erqp9k/OT+8HXwAu4AgMrn8aeM17A4NKLyKMSJjsYMJXWPhq0IAIKCCePCIiBf//vFVxwxihLl40DAihp3fHPn1jJnoGIclFpE4GwMk64CPgaj8PFCS2rXOFpCDFtJvdCmoM1tNLdRMHhx2LdUFoO8TzBRICC6mGvgAARk3IMD8VruH+iPtXxEi6r3cWra//N6kUR209/IQMLz8Xb+NEV5XbgDJMUkJM/l3xoU5mff/u5vO76XaxeMc7wcMz/3rKI2+7qDSHTbhSTW572hEGTW1qWy/Q6lfa7TqYUJ5yxZBv7Ruazf7SHglOUoNnUgzFQPkUoLwOJQD1ozo8kQKwQA5lEfKP8NO6YqCsXJTx3YY0uWyfNarQNBWMUEVClKQqxsmlHiT/8p1MpxlBPwQgUC0r7CbzRFwB/wuNw3mirzmfmqeEStL06md6OYd792j/kmnNuY/2u0/id/3wXD2w/vQWu9g4hYwvQebpQWACaN+opMUBJIQe+sTlm+5DwE+emLOrISHKhHRx+dNZMkdOJAq9CqaCI0KYChQuNyjJgR9tcqpkZvUyURbSRegrPPe+bXHPBVyEtcdqp9/CKKz/N2m2/gSIIStCkkClC95kQzQPNmBYWsBY2DkV8+Ae9vP6CIRZ3tk/YWAMitAQjStsLenOjzwD+i6O43CgtyculiDraiAiMVLtALbgEUMaqXShB0yiYCLrOEKI+0IxpV7Cwa8zysR/2cONFQ/QVPKmn5VmryPQNaIJAQC5/3KABoQWJiD6DNlOI4Btrr+bfv/RLvOiyL/DDTRfxn996Nc4QupkmUYXOU4S4HzRjxhQsbBtxfOahbl53/hBGwCstSxWcDUdV0ysQ1SuACEg5jBNVWo0aehQuF23Db8VTx99+8Rf4l5t+niQXjEBkFeVkCzSHwgIoLQbNmXGxhR/ujbljR4lrVlWoZ0IrsyFoplkgcImKLDx6TuMQodWo5yKDLqQNGVEKDlSF2CoAStAMxkF5pYAAnhkngBG4bUsH5y6s013w5J6WJQLGMG2CQKEL1UseGzSqtJoCPD0BEdqXiBI0j+ZQXCJEXaCek8YZ2Fsx3LO7yAvXjJHkglfwKqiC0jrksK8LFmG6BMHVwOc4jKMFiXARylMTBArGQmERIJx0kYE7dpQpO09sob+c0V/K6Yg8CmReaAUi4CzTKghUuIijOBVai5euOnq28NQFgSkz2c3kzVkbHqwa/vfBbkTACI2gOXN+nYsX11jenTbCxitNZ4yiTJ8gEOV0PPOB/UxxktNajC4BziAIjpVyiDB1xYyABTxNYQQQUCZr77hlx1iZ7+8ocdXKKs9ePUZktHndjYaOZsYEq3CsOiJocLQUUTlPVQsEwZNQD3gQe7AO/Zjmk+U6QQyop6nksC7HArVc+PL6MttHHK88e4SuQt6UsFFABKxTQABlmgSBQeVC4C6mOFRoJap6OcGTCQEjU7cu9wuuA0x02LclVyAZVGwBUFqOFbBucg069T381PlDlCJP7oVmsAZUmV5BoHoZ8P6W3ToT5QIVguAxNAfbAR0rIZ4vGMckZZLQUFoqAGhOyyo6WLc/4qYNnbz8rBF8E3JRRDDWoEy7ILigZbfOjJcONXoqjyMIIRP3Q9fpgi3/iEsxDaC0vNjC7TtKnLewxhn9yUm8I01QY1HxdMkoTroAwzQKghWozAMGWu7oLDe6WmApRwtCyPRBz9mCONCMJ6e0BSNQz+FbWztYMy89aQGDeopje+k58DDl8Tob7fOoaBGDMk2CYKEYPR24HcCJUVpFlLIyjehGaQgC1anr/U8TJALNmVUiA1uGI/aMWRZ15swIEVQs4jNKwzvpPLCB0uhOnE9ItA8RBWU6BUExyzn10aDJclqGWDkdVYLgUR6KS8B1gubMOiIwlghbhmOWd1fImT4qBhWL8QkdQzvoPPAIhfF9GJ/jjWuU9YrBo0yvIBAjpzHFiRFaRS6cI8qkIFAwMRQXCeqZlQTIFfZXLF4B4cSJwRuDTauNgOkY2Eihsh9UUWMbAQOgCE4yLDkoIEybIDCiZzHFGVFahnI2QTBFPcTdgikwq1mBSmLIvOCsnlAHgxhsUqFraAudBzYS14ZQpmYzwmM0gkY8yjQLAuVsFRyQOaU1uFzKip7qDUETeS8T1TpXyLvyoQcvZzPlqVNjUQxRbZjOwc10TJSrjwHgjeOJKIIjx+CZAUGw0ov0AvudF6EVpJaVRukmaAqvQq0GnWWlsytj/1CEVyjGStMoiAMM4Jm1vEIpUqwoelwbZAaAuDpE54FNlIe24NIKKgY1lmNhJMdJxgwIgk6Tc2ojaExOSxDR1UAHJ13gPYDyhpfv5seevZeuUsb23UXe898ruWNtV1PDRhVQZjUR6C9lWAM5P5oaB+opjO2j6+AG2fAObF5DZWr+cpxiSZgBQVCY+vv6HU5EaQUCKxQsJ11QT4W3vHYrv/j6zUwSVq8a44IzR/nld57LnQ80L2x8Cujs7mY6ImV5T0rmBTH6I1aUc0oju+gcmAwYyTMwBm8inqqCpCjTLwgUVgO0zowmlZVprIhyEgVpJpyytMZrfmw3qEBqmGTo7k14/Yt3cPeDZ+IVjHByGchGFc0FDKDMOpmH1X0Zyzszcg/OPP6KsvUppeFtdB1YT2FsL+Iz1FjUOk6UI2O6BYEA3rMSwKmnJWSOlaKcZEGWw8oldXq7MsiFI8nEz9Xo6coZHXcYq5xMYiAbm6yoB1SZVRQwwFUrKjirJLkcETDeTq4ol4d3NI7I4vEDgJ8MGOOYLpGkTLcgUMAalgM4a2gB4lR0GcpJFlihMfiv1gylTg+ewygDQxGVqsUITaE5VHcqUY/Mutvs6xlcuqTOuQvqpF4A8DZqlEvG6TmwlY7BLcTVAfTR4b9jmp3kZYBwglBPQBWcg2KsiDBrKSxFKDkVmk6ML5PLYk66IIqUdZvLfP3OebzouTvBOfCAU/DCp29dRK0ulIpKM4iB+j6o90NxMfiMWaGew4runOvPGEWA3MSoGLoHN7Fo407qG8YoZSMogjeOmeQkZ+YF1bpw5uoq11wySKGY8+AjnXzr3j6YepxgllqoaIdTlGarDkix2MVSMZxkgchkvfu9p5Dm8OwrB+gqerbvjPnwp5bzpW/Np1hQmkYAhdENiikIUR9oDihtySskOazqyXj1+SN0dTqSXOjcv55F629h4ZavMbLvPHZkF854wAAIEEnGzApqdeG6Zwzwx7+0nr7+KgA+t/zXF5bwp+87FVUQYTZaVEil7Aqp0Gx5Kn0q2iMEzeCsMjQS8bt/dwanrajS1ZGxY0+BHftiSoUWaO0FfAIjDygda4TiQsCAekBpeQqoQuohtvC0FXWuOzOh23lKOx5iybovMW/7nZjaCDgldzGaGyBnmoX15ibIcmHZooTf/7kN9PXXIHEAGKf85Et2sHZjF5/48kLKRWUWKuYq/S5XodmiBSxTxRA0jXOKKjy8pYRXcJaW+j++GPAJjD6kJAegtERw3YCACCBMqyQFryCcGCOTVYqU8+alXLLSc3b3CL0772X+uluYt+MuSKtgY4hKIAknWyQpCDMkSFK49OxhFiyoQ2p5VCYQw9UXD/DpWxfgVTCizDZZzDKXxTSdKIsImk4ECrHSsgwNtT1Q36+4TiZKMDGIZVqoghG48oIaXR0e709s0aJgPf2dwpI+Yb4ZZuHOO5l3+0307F4LeQKu0AiYZookm8FLNQNVsJYnZI1iBJTZyaALnUFpNoWFBMExEgsopCOQDiso00YVIgfXvniMJfMzslxO6A6y3BZw4weYt/l7LHz4Zsr714PPwcbgirSCiJRg5hRiuOehLoYGY3r765AYGqwCyvfu76Val7Y9OvMqpBkgEFsQUQ6nqgucqtJsgixUjkMQCIgw7VTBRAoGqpkhzzluOvVdL8WRvSzcfBuLHrmF0uBmwICNwDlahU51NJEoiiBo697Fl4AIFCMQ0baagW7eUeQvPria3/+FDZQ6EiYJX7x1CZ+6ZRHFuH1DxpmcS864jyQp8sPtZ4OCCIeRBQ4kdDRBMAWFOAJrAeW4eBujYhoPWC7a8DUWTlQ8uhtEwBVpRYpgG0GTkmhMK8q9UIrrXHfhbVSTIt966Kq2m2cUC8r/3rKQrbtKPPfKA8RFz9p1nXzl2wtIMmmEUbtRBMj5rZf9Ba+6+uNkueNvPverfOjrr8VZEJQpCwwtwAvzaAFBoEAhVkSUYyIG7woTVaRzYCNrbn8PF375d1l+z38Sj+8DVwAb08ocOZFkKK3He8GahD985bv48zf8Cn//c2/iTS/8F9KMtlOMlbse6OLd71nN2/7xVP7nqwvJPW0ZMgB5Dsv79/LyKz4DanBRwque/t/0livknkkCqvQ6VZpOlE6EpgsCVaEQ+R89nBUhtwWMz+je+wBLHvoK87bdga0NgW0M+NvmP6+TqaBRQGgpaQ5nLNrNtRfcArlDTMZLLv8c//7V/0s9LSCibTav0YmaHbsXIjBaLbN/tJ8lS9aDydk1uIRa6jBMUUAoO4QmE2PQDqX5gkAV4lgx5skDxmZ1+rd9n8WP3Dy5opxUplaUy7QbQ44lR2k91sC+kXls3HsKZ53+PQAe2nEmlSTGGaVdCe3PGmVgrIff/eg7ef1zPkStXubfbv55amlMZJXDFB1NJlBSKNMigiCOwIg+ZoPM2xiXjLNg27dY/PBN9O66D/LkUAfTpiweR9a6DxOPd/JHn/wDXnfNR6kmZT74tRtRFUBpriCyyh3rL+LeTRfhFTIPBacohwiUndBcAkWFDlpAEKhCIVKMARTUOHIbE9cGGwP+JetuomP/w+CzyYBxRdqZIhjxWPEorSl2yg+3nslvfPhtKFBwEFtFCVrlfx+vgsjke+UxSo4mU7QAlFrlvFoEQAnmcNDECs6R2YjC6B7mb/oWi9Z/jfLABkDAxuAcs4WhETQt/zezyAkCQKuFTGBEeRKFVgiaSJC4Fb5l0hqmtkAEZxQlmItBExUs5epeFjz8NRZMBExhZCeIAVdkNjIohpxWJyhtKYgdTScRUKCJ0ly45uzvc8MVn2HX/uV88OuvZ6xWxhqCOSazcNaBW7ngy/+AHRoEE4ErMnsJIh5BUYJgRkSOJhOIgJgmSTJhzaJt/PXP/Bod3XvBZhSiOn/26bdgjRLMLWpgyeiDWLsbXC+znQIGj8UTBDMkNjRbk4Mm97Codw8dPXvx1R5IC5y9/CGMIZhjFCESiF0GJmKuEJTIJAhBMCMiQ/NZwNEkkYWHdpzO/euejimNkGcFPvv9G8g9wRwUCZRNDRDmCgVKUiMIZog1NJmCaf6efg9vfv/f8Jvv/1ve+I8f4LN3Xk/BKcEcXAQwSperg86loBFKUscQBDPCOppMwLTCQ2EHRnv57B3XYQRiByIEc4wCkcnocFVQw9whlEwVEYJgJhhH85lWeQLZWYK5HjSS02Frc6yjgYIkCMz0VwUEIWjCtT9B4CSnaOqQC8dFOUQf53OD8BjKkUQopoZC6ojE84QElEkqAPrYzwIKqChPToglQVAUYZoFgTiCIGhQwJFRliqoHBkEhz4fWQgIYISalamC1CmpUfKp8gdLFDUKoiQGcgEz9T4VsCi5y/lObZBNtW3E3gNgVbC5AcB4wXmDUcH6g2UO/djUZ+uFKDdEmcUdfM0doqACioKAF300hIxRSmSIF1QABESZLkHgaD5PEDSjiVYQBXJQD5qDoYDzOVVxJNaS2cmQGImVfSXYV1b2d+SMFXOqsSePcnKXkUQ5SexJo4xarNScklgltZ7MKrmdChvjwSgCgGJQhElGPE48t4449td3gXiekBfIDW6qotzi/KHPcWYppG6ibKNKqaNUjykljnI9oqtaaFR3NaazbqknVTSuQx4juWASAQU1gAGVqfcCoByHIPBy0Us9TXY5cAfTLQhUjggSD6iZLBHAebLOAbRnN653F65zP/0927h26acYLtXY36GMFjOSQoZzKc5mWJtOdSegoqiAoFgFg2JRppoWBBAVBEBpECbpobA7QiQ5Xxw+n021hSA5T0oO/0OPei+H/7wCwmFnaeAFUcGoNDqfqNJFPj4fV+0iGu8hGp2HrXQTjfcRjfbhKj1EI/3YpAAK4gEFODqIlCA4StoKQXMpcCdB8BSJCuoBD6qThUIeQVauYnp2E3Xtw3bvxS7YSLz0IQp92ykVR+gojBAVhzGFCiauYiQn80UiBTNVqIAeHg7CTIkl40vD57GpthgkY8Yc3ZmIB+NB/KH3KpAWkaSAyQrYtIAb7yUeWExxcDHx4BKikXlElV5cpQs31odNQAVo1KH3agCUYE6qt0LQXAzczY8UBALKZOVANvVSBDqHiUpDaP827Mr7KC9eR0fXHsqd+3A9uxvdSsHVKOIxKqgaUEER8FPvMYcCpUkKJuNLQ+excSpomk50KnwA/NRnPRRGWYSt9GCrnUQHQ2hwEcV9KylNVGFwSePHG1W3iIJaUAMqc+gYLqi2QtBcANwFOILgKOIFMvAecgsaK6Y4Sr70YeIV99HZu43SvK24JQ9T7N1BVzxKwSYgHgGMN6h34C2qgkdoYY2g+crQuayvLQHJaHmHh47kIBw6R0sj4pEFFBrdz2KK+1dQ2rOK4oEVuGoHkllMBmqYCiAlmJVGWyFozgLuJHz5WaACGaiCB0Qg7R6Fxesp9m+iOBEm8cp76Vn4CD3lfdjiGNYmRCqQOdQ7vBoUoV0VJOOmkXN4pLoEJKetiYLJD1UeIUkRk5Qp7l9KefepFPespjiwbOLzcqKxTlAmayp8VJS2Fww4mk1JEeohaOYgL6Cg+WRlRWDRdgrzdhCvvpPO075Lb/8GCr27iMqDlCTD5g4/FShkEaQxGS0pfO+KCuSuUQ2iqE3Jy0OMrz7A+Jp7AEEqXVPHbkvo2H4GHdvOojjxPh5eiK2aqW4HkDbteoKkFTqalcD3gCUEs5yABzLIPeRlj+3eg5x6Nx2n3E7vwocpLn2Acu8OOkyCqIC3jdKJ8gizXUEybhk5i4eqy0By5gSTH7aIoKBgR+dT3L+M0t5T6Nx6Dh07zsCN9+CqEQqoa6MFg2Cro9lEE1TqBLOTCqTgFdSBdowhp9xF54r76FjzXbpW3k1v+QDW1bCAZDE+dXgi5iIFDMqc4m2jDpeXhxk/ZT/jp/6A/Zd/HlProLTnFDq3nUV55xl0bD+LaLQbyQUEvANEaUlB6mg2lQSoE8wScsQDkHkBdPWDlFffQ/ncm5i/9Id09OxqrBTH3qBZAX/wtd5BTgAg4W+YR4WP4uMq46fcx/iauyEpNVapO3aeRtfGi+nYfnqj87F1QQ2TZQGUlhDUHU0nVdBx2legAgpkkCn4vmGi+ZspnPtV+k+/je5l99PRtZeCF/zUBpjWOsgQfrQQNIGACqQxEIN4su79DPfuYfi8b2LGeynuW9E4Yut+5DJKe1cRjXaCCGpb4IgtqDiaTJWawChCOwoBk0BmQDoqmDV3MO/8r9B12rfoXfQwHa6KKJDF+EawBNNwnXmgBvKD5QAa3U5l5QNUVq1l7zM+RXEiaDq2nU3PI5fSsfVcXKWMeEGjJm2xBVVHk4moIlRQ2kAgXvAZKJCX69izv0fvWd+k57yvMH/eBuLiKDaL8AfDJS8TnNyts3DMBrVFm6ktXc+BS25q3GLQs/5SujZdSOeW83DjRZCT+dxOIFBxQvPFhtFaDkLQumuqoBkkJcWdeg+dl36KBWd+na4F6ykXRjBpgdw7tNZJRvDUCQYFlOApyqLJEiXp38m+ieDZd8XnKexfTvdE6PSuu7KxUOCqFu9m+o62wAvjcuHLPE2n/JvAz9F6QsDUIY3ALNxG8cIv0H/el+k75Xa641HwDs0ivFqmRxBLzu3jp3DX2GoQzzQJxIPNwWaQxo2g6XnoSvoefAaFgcVIBj4KgTMTBD7ojNJ0CntoHUEm5DloZ43okptYfP5EuJzzVXo792BRNC2Q1ztpG+HoLFADmXm006mseIDKyrXsuep/6N54EX1rr6Z7/WW4aoQ3oE6ZHoHCPqe0At0DQhMFXtAMvIJfvIPOi77I/Cs+2lhHLkZVSErkB4tgJikgBDP/bFfh0UWCofO/ztDZ36G4dzXz7ns2vQ9dSXHfYhBQd+ILBIHucaA0ncouhGYJAZNAVlSiM+6m7+kfZdE5N9HTvwmXOfI8Jq91cvIERjwnSaAGkhKIUlu8kZ3L1rH3Gf9L9yNX0H/v8+ncdiYmOaGNtUDNbocamk2F3YJyEgVe8An4jhR74VdZds0HWXjm1+hwFchj/Jwb6oejs3Cha9SorGOYgUu/yMAFtza21frveR49D18xeawWh8A5XiLsdSI0XVHYU1e8giGYWbngM8g7a5Se/jn6n/FhFq2+nZKtomk5zF5C0AS5myxRRs+4g9E1dzeuvOm/+zp6H3wG0VgBHx3renSQ5exxWU7TeWHYGPYDCwlmjgc/byelSz7L4qf/J/1L7ydWJc+K5HkHrSEwBK3zQHIRUMZXPNCovU/7DP33PJ++tc/AjfeBEDy5cTE6+P8BW01E00mieO8AAAAASUVORK5CYII=) no-repeat 150% 100%;
      background-color: #2238b3;
      background-size: 205px;
      background-blend-mode: luminosity;
    }
    .leftnav__header__title {
      font-family: var(--text-font-family);
      font-size: var(--title-font-size);
      line-height: var(--title-line-height);
      font-weight: 300;
      color: #fff;
      margin: 0;
      padding: 0;
    }
    .leftnav__header__version {
      color: #aab3ed;
      font-family: var(--text-font-family);
      font-size: var(--body-font-size);
      line-height: var(--body-line-height);
    }
    @media screen and (max-width: 964px) {
      .lh-leftnav {
        display: none;
      }
    }
    @media print {
      .lh-leftnav {
        display: none;
      }
    }
  </style>
  <nav class="lh-leftnav">
    <div class="leftnav__header">
      <h1 class="leftnav__header__title">Lighthouse</h1>
      <div class="leftnav__header__version"><!-- fill me --></div>
    </div>
    <template id="tmpl-lh-leftnav__items">
      <a href="#" class="lh-leftnav__item">
        <span class="leftnav-item__category"><!-- fill me --></span>
        <span class="leftnav-item__score"><!-- fill me --></span>
      </a>
    </template>
  </nav>
</template>

<!-- Lighthouse header -->
<template id="tmpl-lh-heading">
  <style>
    :root {
      --report-header-height: 58px;
      --report-header-bg-color: #fafafa;
    }
    .lh-header {
      display: flex;
      height: var(--report-header-height);
      left: 0;
      right: 0;
      max-width: 100%; /* support text-overflow on url */
      border-bottom: 1px solid var(--report-secondary-border-color);
      position: fixed;
      z-index: 1;
      will-change: transform;
      background-color: var(--report-header-bg-color);
      margin-left: var(--report-menu-width);
      align-items: center;
      padding: 0 calc(var(--default-padding) * 2);
    }
    .lh-metadata {
      flex: 1 1 0;
      padding-right: calc(var(--default-padding) / 2);
      line-height: 20px;
      color: var(--secondary-text-color);
      overflow-x: hidden;
    }
    .lh-metadata__results {
      overflow: hidden;
      text-overflow: ellipsis;
      white-space: nowrap;
    }
    .lh-metadata__url {
      color: currentColor;
    }
    .lh-export {
      position: relative;
    }
    .lh-export__button {
      background-color: #fff;
      border: 1px solid var(--report-border-color);
      border-radius: 3px;
      cursor: pointer;
      outline: none;
      height: 32px;
      width: 48px;
      background-repeat: no-repeat;
      background-size: 20px;
      background-position: 50% 50%;
    }
    .lh-export__button:focus,
    .lh-export__button.active {
      box-shadow: 1px 1px 3px #ccc;
    }
    .lh-export__button.active + .lh-export__dropdown {
      opacity: 1;
      clip: rect(0, 164px, 200px, 0);
    }
    .lh-export__dropdown {
      position: absolute;
      background-color: #fff;
      border: 1px solid var(--report-border-color);
      border-radius: 3px;
      padding: calc(var(--default-padding) / 2) 0;
      cursor: pointer;
      top: 36px;
      right: 0;
      box-shadow: 1px 1px 3px #ccc;
      min-width: 125px;
      clip: rect(0, 164px, 0, 0);
      opacity: 0;
      transition: all 200ms cubic-bezier(0,0,0.2,1);
    }
    .lh-export__dropdown a {
      display: block;
      color: currentColor;
      text-decoration: none;
      white-space: nowrap;
      padding: 0 12px;
      line-height: 2;
    }
    .lh-export__dropdown a:hover,
    .lh-export__dropdown a:focus {
      background-color: #efefef;
      outline: none;
    }
    .lh-export__dropdown .report-icon {
      cursor: pointer;
      background-repeat: no-repeat;
      background-position: 8px 50%;
      background-size: 18px;
      background-color: transparent;
      text-indent: 18px;
    }
    /* copy icon needs slight adjustments to look great */
    .lh-export__dropdown .report-icon--copy {
      background-size: 16px;
      background-position: 9px 50%;
    }
    /* save-as-gist option hidden in report */
    .lh-export__dropdown .lh-export--gist {
      display: none;
    }
    .lh-config {
      display: flex;
    }
    .lh-env {
      padding: var(--default-padding) 0 var(--default-padding) calc(var(--default-padding) * 2);
      left: 0;
      top: 100%;
      position: absolute;
      width: 100%;
      background-color: var(--report-header-bg-color);
      border-top: 1px solid var(--report-secondary-border-color);
      border-bottom: 1px solid var(--report-secondary-border-color);
    }
    .lh-env__title {
      font-size: var(--header-font-size);
    }
    .lh-env__items {
      margin: var(--default-padding) 0 0 0;
    }
    .lh-config__timestamp {
      margin-right: 6px;
    }
    .lh-config__settings-toggle {
      margin-left: 6px;
    }
    .lh-config__timestamp,
    .lh-config__settings-toggle summary {
      color: var(--secondary-text-color);
    }
    .lh-config__settings-toggle summary {
      display: flex;
      align-items: center;
    }
    .lh-config__settings-toggle .lh-toggle-arrow {
      width: 16px;
      height: 16px;
      margin-left: 2px;
    }
    .lh-config__settings-toggle[open] .lh-toggle-arrow {
      transform: rotateZ(90deg);
    }
    .lh-config__settings-toggle summary::-moz-list-bullet {
      display: none;
    }
    .lh-config__settings-toggle summary::-webkit-details-marker {
      display: none;
    }
    @media screen and (min-width: 965px) {
      .lh-header {
        width: var(--report-width);
        right: initial;
        left: initial;
      }
    }
    @media screen and (max-width: 964px) {
      .lh-export__dropdown {
        right: 0;
        left: initial;
      }
      .lh-header {
        padding: 0 var(--default-padding);
        margin-left: 0;
      }
    }
    @media print {
      .lh-header {
        position: static;
        margin-left: 0;
      }
    }
  </style>
  <div class="lh-header">
    <div class="lh-metadata">
      <div class="lh-metadata__results">Results for: <a href="" class="lh-metadata__url" target="_blank" rel="noopener"><!-- fill me --></a></div>
      <div class="lh-config">
        <span class="lh-config__timestamp"><!-- fill me --></span> •
        <details class="lh-config__settings-toggle">
          <summary>
            <span>Runtime settings</span>
            <span class="lh-toggle-arrow" title="See report's runtime settings"></span>
          </summary>
          <div class="lh-env">
            <div class="lh-env__title">Runtime environment</div>
            <ul class="lh-env__items">
              <li class="lh-env__item">
                <span class="lh-env__name">User agent:</span>
                <b class="lh-env__item__ua"><!-- fill me --></b>
              </li>
              <template id="tmpl-lh-env__items">
                <li class="lh-env__item">
                  <span class="lh-env__name"><!-- fill me --></span>
                  <span class="lh-env__description"><!-- fill me --></span>:
                  <b class="lh-env__enabled"><!-- fill me --></b>
                </li>
              </template>
            </ul>
          </div>
        </details>
      </div>
    </div>
    <div class="lh-export">
      <button class="report-icon report-icon--share lh-export__button" title="Export report"></button>
      <div class="lh-export__dropdown">
        <a href="#" class="report-icon report-icon--print" data-action="print-summary">Print Summary</a>
        <a href="#" class="report-icon report-icon--print" data-action="print-expanded">Print Expanded</a>
        <a href="#" class="report-icon report-icon--copy" data-action="copy">Copy JSON</a>
        <a href="#" class="report-icon report-icon--download" data-action="save-html">Save as HTML</a>
        <a href="#" class="report-icon report-icon--download" data-action="save-json">Save as JSON</a>
        <a href="#" class="report-icon report-icon--open lh-export--viewer" data-action="open-viewer">Open in Viewer</a>
        <a href="#" class="report-icon report-icon--open lh-export--gist" data-action="save-gist">Save as Gist</a>
      </div>
    </div>
  </div>
</template>

<!-- Lighthouse footer -->
<template id="tmpl-lh-footer">
  <style>
    .lh-footer {
      min-height: 90px;
      display: flex;
      align-items: center;
      justify-content: center;
      background-color: var(--report-header-bg-color);
      border-top: 1px solid var(--report-secondary-border-color);
    }

    .lh-footer span {
      text-align: center;
    }
  </style>
  <footer class="lh-footer">
    <span>
      Generated by <b>Lighthouse</b> <span class="lh-footer__version"><!-- fill me --></span> on
      <span class="lh-footer__timestamp"><!-- fill me --></span> |
      <a href="https://github.com/GoogleChrome/Lighthouse/issues" target="_blank" rel="noopener">File an issue</a>
    </span>
  </footer>
</template>

<!-- Lighthouse score gauge -->
<template id="tmpl-lh-gauge">
  <style>
    .lh-gauge {
      --circle-size: calc(2.5 * var(--header-font-size));
      --circle-size-half: calc(var(--circle-size) / 2);
      --circle-background: #ccc;
      --circle-border-width: 2px;
      --inset-size: calc(var(--circle-size) - 2 * var(--circle-border-width));
      --inset-color: #fff;
      --transition-length: 1s;
      width: var(--circle-size);
      height: var(--circle-size);
      background-color: var(--circle-background);
      border-radius: 50%;
    }
    .lh-gauge--pass {
      --circle-color: var(--pass-color);
      color: var(--circle-color);
    }
    .lh-gauge--average {
      --circle-color: var(--average-color);
      color: var(--circle-color);
    }
    .lh-gauge--fail {
      --circle-color: var(--fail-color);
      color: var(--circle-color);
    }
    .lh-gauge__mask,
    .lh-gauge__fill {
      width: var(--circle-size);
      height: var(--circle-size);
      position: absolute;
      transition: transform var(--transition-length);
      border-radius: 50%;
    }
    .lh-gauge__mask {
      clip: rect(0px, var(--circle-size), var(--circle-size), var(--circle-size-half));
    }
    .lh-gauge__mask .lh-gauge__fill {
      clip: rect(0px, var(--circle-size-half), var(--circle-size), 0px);
      background-color: var(--circle-color);
      backface-visibility: hidden;
    }
    .lh-gauge__percentage {
      --spacer: calc((var(--circle-size) - var(--inset-size)) / 2);
      width: var(--inset-size);
      height: var(--inset-size);
      position: absolute;
      margin-left: var(--spacer);
      margin-top: var(--spacer);
      background-color: var(--inset-color);
      border-radius: inherit;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: var(--header-font-size);
    }
    .lh-gauge__wrapper {
      display: inline-flex;
      align-items: center;
      flex-direction: column;
      text-decoration: none;
      color: inherit;
      flex: 1;
      min-width: auto;
      position: relative;
    }
    .lh-scores-header .lh-gauge__wrapper {
      width: calc(10.5 * var(--body-font-size));
    }
    .lh-gauge__label {
      font-size: var(--body-font-size);
      line-height: var(--body-line-height);
      margin-top: calc(0.5 * var(--body-line-height));
      text-align: center;
    }
  </style>
  <a href="#" class="lh-gauge__wrapper">
    <div class="lh-gauge" data-progress="0">
      <div class="lh-gauge__circle">
        <div class="lh-gauge__mask lh-gauge__mask--full">
          <div class="lh-gauge__fill"></div>
        </div>
        <div class="lh-gauge__mask lh-gauge__mask--half">
          <div class="lh-gauge__fill"></div>
          <div class="lh-gauge__fill lh-gauge__fill--fix"></div>
        </div>
      </div>
      <div class="lh-gauge__percentage"></div>
    </div>
    <div class="lh-gauge__label"><!-- fill me --></div>
  </a>
</template>

<!-- Lighthouse crtiical request chains component -->
<template id="tmpl-lh-crc">
  <style>
    .lh-crc .tree-marker {
      width: 12px;
      height: 26px;
      display: block;
      float: left;
      background-position: top left;
    }
    .lh-crc .horiz-down {
      background: url('data:image/svg+xml;utf8,<svg width="16" height="26" viewBox="0 0 16 26" xmlns="http://www.w3.org/2000/svg"><g fill="%23D8D8D8" fill-rule="evenodd"><path d="M16 12v2H-2v-2z"/><path d="M9 12v14H7V12z"/></g></svg>');
    }
    .lh-crc .right {
      background: url('data:image/svg+xml;utf8,<svg width="16" height="26" viewBox="0 0 16 26" xmlns="http://www.w3.org/2000/svg"><path d="M16 12v2H0v-2z" fill="%23D8D8D8" fill-rule="evenodd"/></svg>');
    }
    .lh-crc .up-right {
      background: url('data:image/svg+xml;utf8,<svg width="16" height="26" viewBox="0 0 16 26" xmlns="http://www.w3.org/2000/svg"><path d="M7 0h2v14H7zm2 12h7v2H9z" fill="%23D8D8D8" fill-rule="evenodd"/></svg>');
    }
    .lh-crc .vert-right {
      background: url('data:image/svg+xml;utf8,<svg width="16" height="26" viewBox="0 0 16 26" xmlns="http://www.w3.org/2000/svg"><path d="M7 0h2v27H7zm2 12h7v2H9z" fill="%23D8D8D8" fill-rule="evenodd"/></svg>');
    }
    .lh-crc .vert {
      background: url('data:image/svg+xml;utf8,<svg width="16" height="26" viewBox="0 0 16 26" xmlns="http://www.w3.org/2000/svg"><path d="M7 0h2v26H7z" fill="%23D8D8D8" fill-rule="evenodd"/></svg>');
    }
    .lh-crc .crc-tree {
      font-size: 14px;
      width: 100%;
      overflow-x: auto;
    }
    .lh-crc .crc-node {
      height: 26px;
      line-height: 26px;
      white-space: nowrap;
    }
    .lh-crc .crc-node__tree-value {
      margin-left: 10px;
    }
    .lh-crc .crc-node__chain-duration {
      font-weight: 700;
    }
    .lh-crc .crc-node__tree-hostname {
      color: #595959;
    }
    .lh-crc .crc-initial-nav {
      color: #595959;
      font-style: italic;
    }
  </style>
  <div class="lh-score__description">
    Longest chain: <b class="lh-crc__longest_duration"><!-- fill me: longestChain.duration --></b>
    over <b class="lh-crc__longest_length"><!-- fill me: longestChain.length --></b> requests, totalling
    <b class="lh-crc__longest_transfersize"><!-- fill me: longestChain.length --></b>
  </div>
  <div class="lh-crc">
    <details class="lh-details">
      <summary><!-- fill me --></summary>
      <div class="crc-initial-nav">Initial Navigation</div>
      <!-- stamp for each chain -->
      <template id="tmpl-lh-crc__chains">
        <div class="crc-node">
          <span class="crc-node__tree-marker">
            <!-- fill me -->
          </span>
          <span class="crc-node__tree-value">
            <span class="crc-node__tree-file"><!-- fill me: node.request.url.file --></span>
            <span class="crc-node__tree-hostname">(<!-- fill me: node.request.url.host -->)</span>
            <!-- fill me -->
          </span>
        </div>
      </template>
    </details>
  </div>
</template>
</div>

  <main><div class="lh-container">
  <style>
    :root {
      --report-header-height: 58px;
      --report-header-bg-color: #fafafa;
    }
    .lh-header {
      display: flex;
      height: var(--report-header-height);
      left: 0;
      right: 0;
      max-width: 100%; /* support text-overflow on url */
      border-bottom: 1px solid var(--report-secondary-border-color);
      position: fixed;
      z-index: 1;
      will-change: transform;
      background-color: var(--report-header-bg-color);
      margin-left: var(--report-menu-width);
      align-items: center;
      padding: 0 calc(var(--default-padding) * 2);
    }
    .lh-metadata {
      flex: 1 1 0;
      padding-right: calc(var(--default-padding) / 2);
      line-height: 20px;
      color: var(--secondary-text-color);
      overflow-x: hidden;
    }
    .lh-metadata__results {
      overflow: hidden;
      text-overflow: ellipsis;
      white-space: nowrap;
    }
    .lh-metadata__url {
      color: currentColor;
    }
    .lh-export {
      position: relative;
    }
    .lh-export__button {
      background-color: #fff;
      border: 1px solid var(--report-border-color);
      border-radius: 3px;
      cursor: pointer;
      outline: none;
      height: 32px;
      width: 48px;
      background-repeat: no-repeat;
      background-size: 20px;
      background-position: 50% 50%;
    }
    .lh-export__button:focus,
    .lh-export__button.active {
      box-shadow: 1px 1px 3px #ccc;
    }
    .lh-export__button.active + .lh-export__dropdown {
      opacity: 1;
      clip: rect(0, 164px, 200px, 0);
    }
    .lh-export__dropdown {
      position: absolute;
      background-color: #fff;
      border: 1px solid var(--report-border-color);
      border-radius: 3px;
      padding: calc(var(--default-padding) / 2) 0;
      cursor: pointer;
      top: 36px;
      right: 0;
      box-shadow: 1px 1px 3px #ccc;
      min-width: 125px;
      clip: rect(0, 164px, 0, 0);
      opacity: 0;
      transition: all 200ms cubic-bezier(0,0,0.2,1);
    }
    .lh-export__dropdown a {
      display: block;
      color: currentColor;
      text-decoration: none;
      white-space: nowrap;
      padding: 0 12px;
      line-height: 2;
    }
    .lh-export__dropdown a:hover,
    .lh-export__dropdown a:focus {
      background-color: #efefef;
      outline: none;
    }
    .lh-export__dropdown .report-icon {
      cursor: pointer;
      background-repeat: no-repeat;
      background-position: 8px 50%;
      background-size: 18px;
      background-color: transparent;
      text-indent: 18px;
    }
    /* copy icon needs slight adjustments to look great */
    .lh-export__dropdown .report-icon--copy {
      background-size: 16px;
      background-position: 9px 50%;
    }
    /* save-as-gist option hidden in report */
    .lh-export__dropdown .lh-export--gist {
      display: none;
    }
    .lh-config {
      display: flex;
    }
    .lh-env {
      padding: var(--default-padding) 0 var(--default-padding) calc(var(--default-padding) * 2);
      left: 0;
      top: 100%;
      position: absolute;
      width: 100%;
      background-color: var(--report-header-bg-color);
      border-top: 1px solid var(--report-secondary-border-color);
      border-bottom: 1px solid var(--report-secondary-border-color);
    }
    .lh-env__title {
      font-size: var(--header-font-size);
    }
    .lh-env__items {
      margin: var(--default-padding) 0 0 0;
    }
    .lh-config__timestamp {
      margin-right: 6px;
    }
    .lh-config__settings-toggle {
      margin-left: 6px;
    }
    .lh-config__timestamp,
    .lh-config__settings-toggle summary {
      color: var(--secondary-text-color);
    }
    .lh-config__settings-toggle summary {
      display: flex;
      align-items: center;
    }
    .lh-config__settings-toggle .lh-toggle-arrow {
      width: 16px;
      height: 16px;
      margin-left: 2px;
    }
    .lh-config__settings-toggle[open] .lh-toggle-arrow {
      transform: rotateZ(90deg);
    }
    .lh-config__settings-toggle summary::-moz-list-bullet {
      display: none;
    }
    .lh-config__settings-toggle summary::-webkit-details-marker {
      display: none;
    }
    @media screen and (min-width: 965px) {
      .lh-header {
        width: var(--report-width);
        right: initial;
        left: initial;
      }
    }
    @media screen and (max-width: 964px) {
      .lh-export__dropdown {
        right: 0;
        left: initial;
      }
      .lh-header {
        padding: 0 var(--default-padding);
        margin-left: 0;
      }
    }
    @media print {
      .lh-header {
        position: static;
        margin-left: 0;
      }
    }
  </style>
  <div class="lh-header">
    <div class="lh-metadata">
      <div class="lh-metadata__results">Results for: <a href="https://facebookfeed-neel.firebaseapp.com/" class="lh-metadata__url" target="_blank" rel="noopener">https://facebookfeed-neel.firebaseapp.com/</a></div>
      <div class="lh-config">
        <span class="lh-config__timestamp">May 6, 2018, 12:10 AM PDT</span> •
        <details class="lh-config__settings-toggle">
          <summary>
            <span>Runtime settings</span>
            <span class="lh-toggle-arrow" title="See report's runtime settings"></span>
          </summary>
          <div class="lh-env">
            <div class="lh-env__title">Runtime environment</div>
            <ul class="lh-env__items">
              <li class="lh-env__item">
                <span class="lh-env__name">User agent:</span>
                <b class="lh-env__item__ua">Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/66.0.3359.139 Safari/537.36</b>
              </li>
              <template id="tmpl-lh-env__items">
                <li class="lh-env__item">
                  <span class="lh-env__name"><!-- fill me --></span>
                  <span class="lh-env__description"><!-- fill me --></span>:
                  <b class="lh-env__enabled"><!-- fill me --></b>
                </li>
              </template>
            
                <li class="lh-env__item">
                  <span class="lh-env__name">Device Emulation</span>
                  <span class="lh-env__description">Nexus 5X</span>:
                  <b class="lh-env__enabled">Enabled</b>
                </li>
              
                <li class="lh-env__item">
                  <span class="lh-env__name">Network Throttling</span>
                  <span class="lh-env__description">562.5ms RTT, 1.4Mbps down, 0.7Mbps up</span>:
                  <b class="lh-env__enabled">Enabled</b>
                </li>
              
                <li class="lh-env__item">
                  <span class="lh-env__name">CPU Throttling</span>
                  <span class="lh-env__description">4x slowdown</span>:
                  <b class="lh-env__enabled">Enabled</b>
                </li>
              </ul>
          </div>
        </details>
      </div>
    </div>
    <div class="lh-export">
      <button class="report-icon report-icon--share lh-export__button" title="Export report"></button>
      <div class="lh-export__dropdown">
        <a href="#" class="report-icon report-icon--print" data-action="print-summary">Print Summary</a>
        <a href="#" class="report-icon report-icon--print" data-action="print-expanded">Print Expanded</a>
        <a href="#" class="report-icon report-icon--copy" data-action="copy">Copy JSON</a>
        <a href="#" class="report-icon report-icon--download" data-action="save-html">Save as HTML</a>
        <a href="#" class="report-icon report-icon--download" data-action="save-json">Save as JSON</a>
        <a href="#" class="report-icon report-icon--open lh-export--viewer" data-action="open-viewer">Open in Viewer</a>
        <a href="#" class="report-icon report-icon--open lh-export--gist" data-action="save-gist">Save as Gist</a>
      </div>
    </div>
  </div>

  <style>
    .lh-leftnav {
      width: var(--report-menu-width);
      border-right: 1px solid var(--report-border-color);
      position: fixed;
      height: 100%;
      background: #fff;
      will-change: transform; /* prevent excessive paints */
      z-index: 2;
    }
    .lh-leftnav__item {
      padding: var(--navitem-vpadding) var(--navitem-hpadding);
      color: var(--secondary-text-color);
      font-size: var(--navitem-font-size);
      line-height: var(--navitem-line-height);
      display: flex;
      justify-content: space-between;
      text-decoration: none;
      color: inherit;
    }
    .leftnav-item__score {
      background: transparent;
    }
    .leftnav-item__score::after {
      content: '';
    }
    .leftnav-item__score.lh-score__value--pass {
      color: var(--pass-color);
    }
    .leftnav-item__score.lh-score__value--average {
      color: var(--average-color);
    }
    .leftnav-item__score.lh-score__value--fail {
      color: var(--fail-color);
    }
    .leftnav__header {
      padding: 0 20px;
      margin-bottom: var(--navitem-vpadding);
      height: 115px;
      font-size: 18px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAZoAAADeCAYAAAAEuMatAABPH0lEQVR4Ae3dBZyk1ZX38d+59z5PSfv0uMPg7iQB4oRkIbrZbGSz7Js368mbrLtE1903nuzGVuIGgQgxCBbIAAPjru1d8sg9b091fxhBMsN0T1V13+/ncz5VNRaFP+ee89zi8QRBEARBEARBEARBEARBIARB0BTZuru7Be0HOoFYlcirAqgIiaoMGKtbAaWNBYFkD9/JzAuC4H3/57KeZKB0Wb/jea9YVrowFbNC0KVAj4Cr50olzTACCKCy11j/QLG/tlmEb5bXp18GdtFmgkDSy3lS7qxzLKsWzSfVcWCMIAiOzxfvuIZV3S+lp/hSUk5DYSzzCIcIkORKJcsQDqOg3gBgUj8qyP8YlU8DnyEI2oTsfc4ynkjvm65eaJ9z8cuMdQvwmoCpgAwiOlH2AERDCONABZUxICUIgob6R7/ynOz7D/+yjlRuEE8BryAccixBczQBUXCj+Xc73difhcAJ2oFUn1PmcV19dnfxZ1/yM2CXkucJIEeWGsCD1IAKSBUvIyCDGD0AphFEUz9fb9QcEATZvetPSd/7uT/2ef56CpFgDIecYNBMUSOAYES+YJ37XeA+WlQQyN6Xr+bxzP+XX3upJEPPIPdVnpwB5LBXEBQa5UHGgFGQUXIzBDIETFakg6B1IGMWCILq337+NfnajX8lxcISjDBl2oPmcCIMl7fXfh/4R1pQEMjwhX0cLfq5a1eUXn3lGxgZtSCeE2MeLcEAOZABOaIJyDAwAAxh4iFERqaCaQzrhwGlxQWBfv3+qP4/t/xZVo9+RZxhykkJGgCNDEZ4rxV5C1ChtQSho1nO0fr/6NWvMPN6Lif3dWaGABzVCZmpSoAaUMdSRRgGBkEGcbof0RGgAlIBMoKgSe5ev6KcRoVC18Z1C0758Hve7p39SZwBOMlBc4hFPmeM3AgM0iKCwEmqHK7nRef1miXzz6JST5k5etir50gCFIAiOX3AUkBAIUUQqaIyBhMlOlGMAIMoQzg9gGUMJQFSQDlOQbB7sLsDm5f/4+tXdW7b1rM0sqxQdInAotTbRV+9/8z+pEp3LnQV8aU/tz+39PSC70kkotly9MWo/9SY6XtNWIVuFYFsePHZHG78rTc+/fxz6jdQI6U1CWAOKwV8o+RgSRUYRhhBGUAZQnQIzBCqw+BrIYACgA994+m9Y2OF00yUnXLHnlWrvn3XmhVdsEpFVwBLKnWzMMuwIkxSEIFyQfEiGFL+2Pw6L+E/qVFGEYCmdjQABWrcaZ73wG8W/uPm3fPjnRbdirLJCI+IMAgoJ1EQyIpfyJnCaZ25fOqtf/36nrR6FpiE9iOPE0QeSBBJUFJEx0GGEBkE9qN+GBgDxhEZAZRgVvnSHWeVXSlddd8jq9d89vbzzi0V9FxVOXvTvu4VWUqXCOWCgUIBlENElMejQBXhzfLX/LK8m+qhkGmJoBGUAhU+ZH6Pf+U36aChKjAK7BR4QIW1ueUhYKsxbAH2MUOCQC55hTKFC/vW9r3/Tz76C4wXSoBn9pAnKIOQg1SBg1UBHQUZRBgAOYD3gwg1aFRK0NLW7Z7fsXt/39L33HTVeXGUP21guPviezb2L7OWJc7SFztAaYic8lRUEJ4nX+Ov5KcxeDIcQMsEDYAhx+L5Q/cRviYvpIjyBKoi7B4fZHNW415V+a6HtcBuYIBpEASy6gplCl/9t387/7SF219LEtWZO44MHhAmKQ2SIkxtwukoMAIyBAwjcgCfDwFZo0664LaHTu/64t1nnke9+MzP337uBanlTIFzvacIYA0UI0WZHhlCHwO817yMNTxEjRJAywUNQEyNHXIab7Zf4YD0EaE8EWMBYQqKss5Y1lq4R+EbKfJDYATwBMFxcvNW8ah0xK5iIcrcolMFkPMYKih9QD9gaNAcyFFyRGogI8AwRgbI/QDCKDCKyBAwzrQJ/ufWS1099pd86juXPX3z7r6nZXn89OFxWWYNrqOoOB5LmT4Z8Fp5L2ewlgqdtLKEIqv0QV6tf8/fyR8R8cR8zuEEOMvnnJXCjwO5ovtR7rQi30G402V8BxgjCI6BXH6DAvCMNevkz3//Yz8fj8kKkJTgyQjA46xoWwBEEqAO1EArIMPAIEYOkPv9wDhQmXr1BE/qextWnvuhW64+f/POeS9Yv2PeVRksLxcoOwMIGFFOhgThNDbwPvNiuhgmwwG0bEcDYMmoSwe/aG9ho5xKAWUaeOPZauCutCZf3rOOO1S4H1CC4HHIolUKwOtf84P+v/iNj7+RkVInkBNM53Hc4T+mIBXQcZAxiMeBySCSxkzoAFADkkbNQVv29/R84JZrTt+8e97131q79PkYLoosncZA7JRmUIQa8LvyB/y0/DPjdAK0fNCA0MEwn7Rv4S/MuyijTBcVEEAMVRV+oMLtqvIZ4F5gkCCYIhf8uALwyivvOeMPbvyv11MpekCZSYE5VCqAAh5BQXJgMnxERlAdBIanPg+hfgDVFPDMIg9tX1z87D1nPfPOh8684f7Ni5/rvZwLUC4orSBBWM5OPmReSB8HyHBtEjQQkTDAYt4U3cxOlhChzLBHVLnVeG4e7JObgRGCOc2NlGm48fnfWUg9ioAaMy3wUwUIj1IABOgCelA1gAFyIJ0skyCMggwh/gCqEyUjj86FoEKb+M7Dqwp/d8fVz9r24MIbSAo/tmsgXl0uYouRAkoryYBnyK0sZCdVOmgnGRGL2cIl+nU2y2uImHGni3A6lp/vqOpWb/nynsXyhTp8ExgimHPcvnk0dEWVhSCeoNl0qjyHSKNUC0AR6AFdgWJABEhAqqBVvKsiZnJF2+T7yQr70KgC1BBt+rU9P9i+oPjNe8666LaHlr30we2LXpqmnB1FIAK9nUorUoQIz/Pkc4DQbhQhw/Ec/2m+Yn8SxSAoM02BOGEl8HOnbNSf8ykbxg9wi4p8TOD7wDhzQuCWfRdWnlkR63QB4AlakR56fVyCahnoQFIBBAAPmBRE6iBjiB/BuxGIRoAhxA+QR/ungigDUmbIr9/03FOHHu77iVsfWPby2HIlQCGCUlFpdSmwWrazhnVkRLSjjIg1ej+djDBML5aTQ4WGXIAiazpXsgb05wTuxvNFKcgnpcBawDNrBXL5jcrPveBrpTdee/P/Y7wYFgFmJzlsJmSYlCPkqOSIVEGGER3EuwF8NAwMoYxQYBio8xR8/BsXlbfumn/DR799/ktG6/bFkdJdLihKe6kgvEBu5m/lddQoAgLQNjMaAINHEd7t3sPNcgNFlJYg1FX4qop8PEr57Oyc5wTOD0BhWHuBCFBmo0CBfLKERykCWFS7QHtQVkNisIkH6igJSp2IKsgAogOo3U9eGAYqCOPAKEf59HfPP+O9X73iVQ9unPdTKGd2laA7VgCU9mOg8dyMJQOEduQxdDDKGl3LFxtB0yKUgijXC3q9wmbj+S9V+ShwL7NG4Mgh7ZBefAiaNjQDt2jLoQCCMjllMuYBy0EEvEGq+VTQVIARjB1Mk6jy/YdPWfr7n7/2RYPbup9jnfbP68ypp5YkAxHBCIiAESaJIrQ2RXDASjbgsbQzwVPWYQytyRtW55bfENU3E3MzVt6rwteAUYK25rIesOQ9gANSggB0qiYJRxOMdwhd1Wph2cM7F527bseiC/YNdS99zXn34s8Xxusx47UCo9UiY7WDFTNaKTJUKTFWLZB7g5+ozINXEMAYpoJIaSUGWC5byLG0s5SYFWygm4wEh0VpNaIAFKnzYtCJ4h6FD8WpfBTYR9CWXDQEL7/qni6qBfukQRMEAhifgeZDo539D25dcvEjuxZfPBEgfaA46/EIAnQV6/SUapj+IUDJvWlU5i311DbCZqRSYvhg8NQKVA4G00SNVYtU6hGqNCiThEPdkIgy01KEjEkCdDLMyaAzfHzWowcQlCpgESLAoTwV3gtJDtZAZJVpJTQIXHywfKS/Jrl8RHM+DKwjaCtyyQuV7/7du14ex/kVQJ2jBYGgGJ+j6IGhrkVrty29aP2uhReN1wpdzipGPD+KAIgCIAKCYmSyEEgyO1GOWhJRT10jfIbGywxO1ESQUU0d9SSi2vh5g+pU6BxeAJx4ECUI8xnkeXyOpbINUF4qH6OL4RntanJVMq/MFEPOKPO41byCGmU2s4Zv6I8xQgcRyvHIvFBwGacu2sS+4QXsHemd+VsbBIADAh8zKv8KrCVoC/K6X97p3vuWD766GKVnAylBcDibZ6joroG+ZfdvXnbl5j3zz03SqGBNjjHK9DgUPiL66PsGARTqWcR4bbLrqUzUwSAaHi9PVImRarERTlluSHNLltMgAuY4u6AEYTWb+DPzc5zH9/E4QKhRQhFmmjBzFMHgialiUIScb3Mtv+3/hSH6j7mz8SqU4grv+Mm38dwLb2HrvlX84cf/mLs2nk/BKSfJuCqfVZW/B75H0NLkNW/a2fH+t3zotUVXXwmSEwQA1mcounugZ8n9m5dfuWnPgguT1EXOekSUk01EMVMloiiC9wfL4FWoJlFjHjRSKTJaK07OhyZq4nPjOC7NLKrgG3XUUZxRBFCEFOWP5Dd5lfwb4/Qx23UwxN/r2/lnfQsllGNRqQsvvuwW/vINb4U8gtIoX/r2T/LWD7yTcgFAOYkyVfkE8A/A7QQtyWW5iVHKIEoAhIBBNN83ETD3bFz19C17+8+vp67gjCdyOc2iKuQHiyMJYIzSWazTXaqxfP5kGOVeGt1NmrmJspMdUKV0MHgar9WDnVESUZnqkNIccqBb6pxu7ieVInAokWYrT8xF8j1U38KxEgOj1S7II3AJoAxXulGawono64BXCHxCkb8FfkDQUuR3fmv9oj964yd/puDSMqDMTYFRj/Hp0Ejn/B9sXHHlwzsXX1JLXCma6mDakYgicMRxXONVlCw31NKoETjVg4GTxAxVyoyOxfxK9Te5OPkmtawAaQZpDl7BCFjDbNLBKJ/hdfym/wfKKMdCAVXPG5/3YW648lNs2H42f/6ZX2fX4AKcVZpsTOAjxjQC52GCliB619+eyryR14I65p5AVLF5MjZe7vnBppVXrtu2+NLxetzlrMeIMlsdCqBDCwkopMScyoM8N/8spl4nq+ZQT9BaSj5Sw+8agiwHYQYICDPKyKH/XWPqjNHFm/3HuIOnUUCPq8OsZ1CMlCQTjNAImRYyCLzHO/kbYDdNFYhu/aOLyM0NgGOOCQHj06QeFddtW3reDzYvv3pwrGOBszlGlLlL8Ahnyf2ca+6lJFUQQUUoZGP4u9eh1QREmHbqwecgwkwQYLxeppoUEFF2sZz/0F/kq/pCIkBQjpeqtHTHK45NQzvkr8cH+AAwTlMEolvecTXePwewzClhk2z9jkVn3b1h9bP2DXetEFGs8QQAQoajSIUCdRTwavixp9/N/Pm7IQcQpp/C4B6ojoIYppUo2Ix//tKNfPS7z6cjVoboY5QCRQCU2cpYEOFuQd4BfJrjpB30qNIjUGRSAowCBwiOiejmt12HckUImjkyhxGf7RvsWXz3+tXXbNi94CJVcNYTPJbHoAgAuTe86nnfY9GqPaAWVJl2YiCrw96tkCUgMu1B8+7/eTP/dut1dBXAABZlLokyPm28vAu4kyfgu+jP+rjCC9dV53GONSxVZZ4IJSbVUYaBnSiPqHKLV24DdhI8LgdSBhWC2UsAmyfVaqF8z4aVz3pg67Kn1ZKo7GyOGJ5AYPAcouA9ZB48M8SDRFDug4HdIExv0KhifUYMRChzURLxMtDnCfKP3vCXwABTagu4uL6AnykrL1FhNYA9+iraQxYBZwDPFvhZa9iP50uqfBC4leBxg4bZLTwPs2H74jPvePjU5+8f6Vwa2ZzI5bSiQKHcA2NDkNRAhGB68xboAv0d43mJyeV3h5awTubzK7HwUx05HQoIx0mZj/B6EV4twmeBdwL3EjQ4lCIgBLNx2J8MT6wr377u1Gdt2LXgYo+Y2GW0sEAVrJ0Mm6QKCDMgUMBzbjqPTxfnMaDQjwflhEUKP64511W28Bfe86dAEoJGNEYJZhPjM/XG3Ld+9ZV3r1/17PFa3OOsx4knaJOwKXXAqIN82rfQAgUMZIuFvB9B6UeZPgpi6Ow6g7chXK7KzwK753jQMMuCJnQxBwa7F333oTXXbtk7/xwjvh2PyULQRAVwMeRVgukPmXQZ+D4gZ8b4FARu8I7Pbt3OK4GtzFEOJAYlaP9ZjM+NTHQxT7vnkVXPHU/izsjmBG0sLkK9AgjBNBHIlgq+F8hPUq55Ll9R5n+yUW4A9jAHORQHCG0tPHg5ONzV/50HTnvBxj0LznPG0+4hEwi4AiggBNPBQ7ZEyOcBOSeNerC9XObm8T6ElwEZc4wDNQTtyfgcFX1w87KLvrduzbXj1UJvGPbPEgJYByjBNPDgeyCfD3hOOvWNul7ht4B3Mcc4wBC0H5cnlWqh4ztrz3jBup2LLjNomMXMNiKNOkGBAhFkiwQE8DSNgd/0yufn2g3TDhFBlaBNiHpsnm7dvXDNtx847cf2j3QueZIbloMgUMjmgZaAnKZS6Eb4A+CVzCFhPtNOrM99buWuB0951l0bVj0nz20cu5xgFlLA+xOd0QQKWgDfJ+BpCQIvF8MzgW8yRzi8KiC0tsBlyeh4ufub9591/cbd88+LrMfZnGAWy1NOTCAKebegMa0UNCaHX8wM95cMw4CfC0dnHlVDSwvPxmzbveDU2x444/qBkY4lc6GLCRTSOgjBU6WgFnwXLUUB4/mJ2PNMEWoC6wVuQ7kF+C6zkAP1tKbAaK6ov/fh1U+fuKfsusybeI4M/AP1kNQAIXjqNAZfAjytxgJLMwWFU4EXAG+zwje85W+AzzGLOIQcpQWFBzBr9Tj+9trTrntw29IrrPU445kDAjFQG4P8hL4qINCpkLGAp2UJjzJeeY5mPAflw1h+HdjHLOBAUtBwsWYribL64GD3gq/df9ZLdg70rpljXUwgQHUMcg/G8AQCzyHCIXroVUtCuxEA4adRzspyXgVsoc050DrQRcsI85ituxas+fp9Z71spFrqD0/4zzEikNahMgJGCB6HBwxoGXwn+JKgEQ2iQB1MVbEjoBHtS7kisnwmHeF6YAdtzKEkBK0RMqLZ2k0rLv3W2tNfnHsTz8WQCQRGDkCeghiCo3jwXZD3C74TMBxBATrAi5AnoAJ42pfhQp/wntoOXgYk7dzRJDRXYHyuKnz3gdOfc+/Glc8VVKzxzDGBMVAZhfFhQDhMoIBAtkjIFwAG8I16QuoApa1pDoWFvKi0hJ8F/ok25RBTQb0CQnDy2TxLkjj6+n1n3vDwzsWXOBOe8p+TxEBah6E9oAoiBEeFzFIhnwco4PnRlFlBc8hzfgvhk8C+dn1gswIoQTNCJh2vljq/es85r9i6r/+MyOUISvMEXs0T/7gIGAGEaSUCSQ0GdkKegDVMOwGMoGLIgRzhaAYQlJajU7cu9wM5c9UK8bwC+DfakEO0gtIE4VLM/YM9C2/9wdmv3DvUtaz5ty4HRjwFk/B4cjFInkEtA2+YPgK1MRjci9brIMcwVJCncDONKNiMOB2nm1E6UQ5RFKFGGY9tzVuX+wHPnKbCq9s3aKwbJ8sITiKX1Xbt61/51XvPeeVIpbSg+evLQeojTu3cwrVLv0nuHQACIAKAihDtSknv2AtpBiJMH0VrCdkdD0Oag/Ckqt6TAsLxe3n9d3mReRuS8ShLTpUyb7cf4CE5nwilZRjI5wtICBrgfIFlwI42DJp0hEyU4OSIstq2ifXlm+8991XVetzd3PvKAhFFAGs8TnIilxIhAKgCuQfvIVd8LYPUQy4gTB9jIFG0kkGW/8gQ0zTDe0U4fmWp0SEKemTQVOjAkaAt2M34MuAJoFuFs9oyaP7s6y8e+ZUrv5LHJo0AZeYELq9v3Lb43FvuO+fHk8yWQsic1AfgAMXIZIkoAGnuqGeWSlZmODHQMUYuRUgydKLIPZr7Q4EjAobpZQSt1EEVjAHhyRnhqfJYHkvIcShCSxHIOwED5AQQAYtpQ+62HSuSt6jUgRKgBDMWMg9tWX7xN+4/4yW5N4Vwncz0E0DMkUHiveD1YBnSzDFSLTI6UePVmNFakZFKkbFagX3VLq5KDvATV27Gz18GWU6DMEVAhBkhgg6NQZaDs0wJDGhJwDMlUKVIG3IlmyagM3p7X3jaP68/sGnFZd/44ZkvQ8WGZ2ROIEhEpwoE5VECWW4Yqxao1GOqScxItcBwpcToeInhaolqPSLNLVluJkoeveHFCFQF8B72DcHC5WCEk0IEkhS/fxiMcJhAAMdhAoE6bcgZpA4yDgjB9BIU45O1G1de/s0fnvFSBGueNGQCEQA9LFR4tEPJvVBPo4ly1DPXCJShgyEyXn60M6klEbXUkUxUmoMRkEPVIICzekTzYBAwAjsH0NU1pFQA75lx1uB3DaDDVTCGKYGCGlDhkCATwx7akJNIEzSvAIZgehmf3rd+1dO//eDpP4aoNaIcEkwFCOZgGcWrkOV2srw5GBqNIBmplBrHXaO1AuMTVanFjNdjkswggB7R8RyqQqTHP5Sv1sk37sadtwoEUGaOEbSekm/YxWMF4kEAJUBAc4aTAzxAG3J33r9UudZVcLkhmM7LMev3r1/59G89ePr1ImrmYMgc6kamCkBVUAWvQiWJGKsWGas3AmSi4smjrkZ3UqSWOLwKuRe8BwWMHOpSIqtMO2PwW/fh+7swy/ohzZkxIuTrd6JDFXCGwwQCKJADjkBAPWtdDztoQ871wKc3Xjj66gtvU5ICJygQYGom860HTn+xiIoRneUzE4DJV+HQ5zS3jNViKvVCIzTGapMzk6GxcmMoX6nHjV+TZpYkE1TBmENBIgCiWHOwTmI6eiX/4VYoxpj+rukPGxFwQr5xD37THp7gP1zgQaqgRUDDkXJ9Fx+nTbn6Ltj5YHGIyzUlOeFONbB5/cGpwT+CGNFZtBoMcth6cJabRkjUs4gks42OZGi8fLAaQVKtxxMVUUliaqnF50fNSmSqgNgpLcPI5AOUd2/AXXQKZn4P5B5UOWFTKZpv2E3+4DYahODxKJhRxfdJyFzYVjX8D23KVQ2YNX6ElAxwIWhO7AvL1m1efuFEyLwUsEa0PWcmRhEUr2bq2MqQedvoQEarxcbcZOJ1alZSaAziD75muQCgOlkcdszljIKhfdjJeU1253rsmcuxKxeAtZDnPCUiYA1aT/HrtpNv2QcCiPAEAgN2DPIaaBHwzFmJ5y86lrOXNuU6lkOn+CGYCpqnLDzxv2nH4rO+PhEyCq4FQ+bILS4UAAUEIVeoJVEjMMarxcaR13C12JiXTA3jSb0hb6wGG3IPHD4zMYo1yqxiDGQ5+Q83o/uGsWuWIH2dYAAPqAfliclhSZvl+O37G52MDo+BtRyDIAV3QEmXC3ORCkSGr3QY3kMbc/McfHn9paOvPueu8c64WsIbguPksmT77vmn3nLv2a/Mc1O0xrfMarCgGFEUoZ5Z6knUCJTqRI1MBcnkcVeJetZYC278fJo/9u+VwiTTCBXmBpFG+d2D+P0jmAU9mGXzkJ4OpBhDZEAB1aN+D5Bk6HiC7h/B7ziAHxoD5XhCJrBgBsB2QN4H5MwdBiTlIfH8dAI12phLKvBIpS9PE7ePAguBnOMSrvrfvb9/2c33nPeqehp1nKxrZUSOnJmAkuWWqQcSG6ExVi0wWikx2JiZFKgmcWNuMvm8iUUfM9g/9HrUzCSwBrzH7xpolJQLSFcJKRehFCOxo0EVradotY6OTdRoBerpVGIbMARPgdulqBN8F5Az+1mQcYh2aJlElgF7aWNO1tNQNPk+wAIpwTGHzPBoZ9/BTqZSj3uczWfkKXgjCnJoNVhVSHLbWAkeO1jVIsOVIqPVwkQVD1YjVLyXRuUKqiACZqqcVYKnMmcRALSaoON1GgwgQoMCKPjD/gt3lhMQCJBBtFVJlwq+F9BGzT4GUDAD4HYrkrIS0f8GuRbY2L5B42lYu/b0PZc9424lNxyDwPqsXi8Uv3rv2T8+0TEsjI4zZARAjlwJFhQEBMi8aWxs1dJoagg/GSgjjWF8ufF5qoMhzQzZYU/BGwMCMDXYNwTTbSqxn3hNzxBMJwFyiLYr+biQ94MWOURpX8IkDzIG9gDYEaXBAHCqop/0yHXAAdqQy4WG/3rw9AOXPev2cepRDHieWGDU+8zYiZB5xc6B3tWxy580TI5+eNFMXaeSZo4ks40aqxcad3KN1A52JxOv40VqU9etVBtPwYPIVHHke2OUgiEIZjehwR5Q7DD4TvBdgi8CBlRAaDMeJAVTBRnVxiseMBxB4FKDfsyovAyo0GacUxpKqe73uR01sOBJgiYQnYD/+v1n3rBx98JzYpcBIKJHBIki5I3trIMlVJP40WtURiuNMGmsB1eSyZlJNXGgNCgcCieOuE4lCAID5GCGwAwrCKgFDO1FQXLAA8ok06jHJXCtyfWfXcYbAE8bcXFdAfjy7efVX3vdyr1nrN6+iCTiMQJB1OCy2n0Pn3rV+p2LrywXEqZQSx3j1UIjOMZrcePZkpFqibHGVfSFxtPxuZep4AFVMHLYMb5RjlEQBDJVUySjPcmhOhaZ48aJ2gC8gzbiakUeFTu/Gbhgzv9fVxFQAcyhH9c6pfruu3549iWfvf3C68brMaNTYTI8PvnAYpJaktyRpIbcHxkkIjSIKJGlBQUGD9SJKfB4shxUAWFGGQEB9InHgxOlyFN+KJcjWHIyHIKnbQlzgtDwNlFZD3yMNuGMClP4yNev2PIHr/9Uwuy+NFWYZB4twQAZUAcSIptgzSjKAdBBusoH6JAD7/i7Z57xpW+f87bhasEAiDz+avDUFfRBGxGgoh3s4HQqdPAYCj09OZEDVWaMAEkqZDlPqFY2pIBwfERgvOao1CKMKFMw5NQoUaMDIWgDoqLvSXLZCnybNiDn3KBM4fzVO6OP/+E/vpGx4nKElPZ2eJAI4B8tLznoGCoDGB0hZQjPCDCI6DAdpWEg5TB37Ty9+6ff+fJbNOOyMC+ZvQTlaKqQ5cJvvWGQs9ck1BNhpkRWueehIht2uCdZQReeCmeVBzYWeHBDTOR4HErQVjYoPBvYTotzh1+1/tC2JemB8d4t/XZ8Jd7S4g4dbSkCCJMEUESqwDDoOCmjwADIAIYBhnSIROuIJkDO0QarHO7OTSvNL3zs+vdIzmVxCJlZzWM4mgLWgnUCGBBhxhgFDNooZVoJGAMKqADa5qdPwRoR3q/Ii4E6LcwhwuE+e9OlP/yZF996pdStAErzCMBRQWIapQCSAOOI1ihQRWQYZB/4ARIGQSvAOGiVCE+D0tDPcfm/7/6pt2d59Kq5+7R86GjiWImsoqqgzBxVQJGpmk6C4owigKgSzALKtaL6V8CbaGFOvHK4j9125fb/88LbtiF6CirpSR7EW8CACkKGkjZeY6kBQygDCIP06jCiYyhDGB0FasyQt7//xT8+Xo1+p7usKHNRoAjOeVwjaGhbChijiBDMJsIvA3cD76dFOYQj7Bvt8A9tX37XWadsOYV6NF1dzZEdCQqgh90AmYKMgQ6BDONLI8DBGsDoAGUdATLAA5BwUrzjo88/7QP/e+k/9HaqUdpLkgkCRE45QYFC5MA52p41IKJMJ++FegJewVmIoxBmTfCXGLkXuJsW5DDC0f7iw1ev/dff3XxlZHQlXpLj3whXATFTr4KQA1NHWTKOxiMIA6gOYO0A3Z3DoAlQAzJawL++75LyP3/y0g8sXswSlLahCEkGK/r34L1lx8D8E3zYM1DAWW2UqtC2VLAWjIACwolLUqFYUC48c4zOzpRde4us21zGWbBGOTkCEfryTD+wa508Bxigxbgda3mMHWvPSn7r515w8xnLv/jTjJcdQgYIU47qTgyCAlNBIXXUjTVCRMwBvB8kYxiRCqpjwNgRWZLkUBmg1Xzq3vP+on8+V6NKO0kz5bVX/y8/+4J/w6vwL196E//zvRefwG3MgSrEUx2N0r4UsFYRAVVATjxkli+q80e/uJ5nXDIINmdsLOaTX1jKP3xsJV4FI8rMC1TBGC5Yfq7+A/A6Woxbfq7yeF79zms2/O/v3PXF1Wt2v4jUxkA+WeJBKogMgg7hoyHUjQIjiA6jdgCo8yhLu/n5v3rda9bt7PqleZ2KajuFjLC49wC/cO2/M3/eThDPm174L9x83/Op1EoYowTHTxUiB1Gbz2hQsAaMQK6cEK+Cs57ffeNGnnH5fsgsJI7Ocs4bfnIzewciPvDppZRLnFzBa9Nxvg38My3EpeM8oRf//ltv/9Nf+d+9jNpTERlD9AA+HkRdBUiBjFlmy76+0773yLK/6i0rqrQXgdw7kiwGkwNKksZ4b0A4AYFzOlG0PWMUkenoZuC8NVWedsEQeAteaMgEYuGFV+/nEzctIc/lZB+hhc4m5h1JVb4F3EeLcFkuPJlf/8sf3wRsYg5QT4zjX4pllghKu4mssm+kh7/5/Fv55Rf9UyNg/v6Lb2asVghHZyfc0SjOKr7dt86sRYQTHtKoh45yTqHgwXMUoaOUUyp4RsctJ1GgYCzzSt3670bluUCFFuA6ugim5J7fRvT5tLHYKV+4+3nc9tBVqAqj1UJTlwFUBQARbf+gcUo9EdqRGosKdGYDRMwjoYCgJ9DhwZZdRXbvK7B4aRUS4RDPI1vLDAxbirFy8gXqudKj7wbeSgtwXhUIRLka4bdpf41gqdSLyNT7Zq5YR/bQ+3buqiIH1tBmBDUWUOLxAboGNtAxvJWSXs8YBU5E5JSde2Pe8z/L+f1fegSJcyYpe3aXed//rsAaECFoEoU3Gy83AV+kyZx4Ya5TodOL/iNQYpawRpu+mPDMs2/nLTf8Lbka/v7zb+FbD13RnmEjUIg9SpsQwYtF1FMc20PngY2Uhndg8xqIwZkMPCesVFA+/uXFHBiOecXz9tDVnbJpa5kPf3YpD28pU4iVoKmMN/q3InInsJcmcmqZ88aL+q6OCheqMA0Cr0JXqcrvv/JdLFvyCAj89sv+gtf/wwcYrnTirNJOBCjGCtoOAeMwPqU8sp2u/esbQWN8hheLNxEGTyzptKw3i0DklC9/ex5fmag4gmodIkcImRahcHqk+hfAjU1eplHmMoe8IK/ySypMk0CByGV0FschiwDoKIwT2RSl/YhAIVaU1qQiYCwmS+gc3krnwEaKY3tBPdoIGAdTRJRIUqaLyGRnowqqQkdJCVqHACm83iBfAD5Jk7gcYa6q7qdHO/UvSiWmMW8DIzAw1sW/3/xGfunH/hFV4X23/h/2jvYRGdpSK/4TuopBxWKzKh0HNtF5YD1xdRDUo8aBGB5PbFJUpj+MRZSg9SgI6J/1WfkGsIcmcH2WOcsu5I9S5QJVgmm/JRg+/I3X8I0HngkKW/YvI7KKtHNHo7QEFYuKIUrG6BjcQsfAJqLa0KHhvxieiAAFk4ICAhB4FbwHY8CIMtsI4GH1/lz/FPg/NIHbnytz0f7N8rwFp+ibUGZAIALWwMa9yxAgsiAA7Ro0BW2JFWUQotownQObKQ9uJqqPosagxnFslILJmBTkXjAC/V1DDFV6yf3sfcBU4MahnfIZ4NOcZG54pzDXdPTTOREyfw5EzJhARCm42RGahQhQmmIqRIgrA435S3loKy6tomLwNuJ4CBwxowlLK2P81kv+mqed9W1uf/jp/PlnfoXhSs9sDRuZt1L/DOQbwCAnkZu3kjnH57wJ5RKC4JgoxYKiJ3uDzFhEtTHYn1xR3o7N6/ipAf9TFZGiBJU6/NTVn+cl13wU0iIvfuZ/sm7Hmfz7La+ho8Cs5DPOUOG3gd/iJHJ5ztxiOcegv6UEwY+mj3Y0Hj1J8xdvY0RzyiO76dr3CMWx3YetKDtOlCNlUhBFCQigFlAil6DKrCaqb/bCfwPf5yRxijJXjOzDdHbxp1KglyA4RgKNjgZlxqiZDJhiMkDf7g1UNhygo7bniBXl6aE4MiAoxfCZ79/AFWu+z0Vn3M4P7n0hn73reooRs5ooJYG/3LNIrgUSTgK3d6EwVxQjXhlV9cVKEBwjBZGZu8rH2wg1jrhygAWbv8Oy9V+gsm0F++rnoNaAGKaTAFYzILBGOTA6j//3gb+lv3sfB0bmU88cziqzmQoIPHPeADcC7zk5M5oB5oRinT4VfZtaguC4OAvOgSrTRPDWocZRHNnFwo3fYNGGWykObQeTomY1ahyQMt0UsJJjhGAqbNLcsvPAYowBZ5S5opDo74nwOWA3M8wVU2VOsLxVlbMIguOgCnGsWKOATEPARCDSeP5l4fpbWbDpNuLR3WAcuBhEmFmCJcOhKIKghAeMFWOZeyyr6qP8LvD/mGGuPs6sVx2Rs3qW6VtQguC4qApx5DEG9EQCxsWI+sb9Y4sfuZn5W76DrQyCdRCVOFkUsOKxeDIsc1egHlyZ/ytePgjczQxyUVGY7Uq9/F6W0kMQHCcF4miqo1GOi4ppBIzxGT277mPJRMDM2/Z9TG0EXAGiIiefYMmxkpOqRZjLAhHK4vhD4GXMICeO2U24Jkv11TwFQaAKhUgx5ngDpoBLK/RtuYOl675Ez64fIGl1KmBKNIsqOMlxkqEaEwSq+lLgBuDzzBCnqsxahkhy/hjBcYIUQEGEOSRQnepoLOixPAPjYqLaKAs33dY4Iuva8wD4DGzcCJhmUwRnPFY8KCAQBAp/LCq3AhVmgEOF2ao6yMvLffpcPE+ZKtQTwTmInFJPBfXh+zbm1tEZGDmWFeUB5j/y3YmA+Sod+x8B9eBiMI5W4iRvFEEwxSiX1or6U8C/MwNcvajMRuOdUuqp6++gJxYyWS68/Ln7eNWLdtE/r86mbR188H+X8937u8P3oc8FCoVDM5rHX1Ee3cPCTd9k0SO3UBzeCgjYCBBajQKWyaBRDgkCl/Mb1ZJ8Ehhimrk0FmajZQO8rlriIlWesloi3PiSXfzOLz5Cgworlla54txh/t+fns037+qlVFCC2b7e7LEWcn/kinJ5aBuL1t/C/E23URjZBcaBjQGhdQmWvFHKpCBQAZdyWlfK/wX+imnmukaYdayntyb66xiesjwXFs5L+ZmX7gAEEgNTip2TP37H/d14bzBGCWb31pkxkJoCeN+44LKxorz5W7jKAJipFeU2oIAjx5ATBIdTAUHfIiofAfYyjZww+9QtP2XhTE5AlsOKRTX6ulPIhSOosLLxczn7Bg3GEMxSquAKESZy9Gy9n4WPfJX5Ww+uKA+BmxrwtxXBkGPwIATBERRW5OjPA+9gGrkMZTYxnl5n+FUVTogxMDgSUU8MxY4ccg4RZWjMMV41GCGYzSwsGl3H2V/7AMUN9yFp5dCKctvyODIeTxAY4Ze95z3AbqaJQ5lVROQNKnoKJyhyyqadRb7y7QW86sXbwFjwAk4B4dO3LmJ4zFIuKsHspAhxDOft/SKlka+B6W0ETPsTXPg65ycWLDoYNsAfME2cEWYNL9Kj8ItME2fhbz6yEms91z9rH8VSxsBQzEc+s5z/umkxpQKzXTg2M9ARZ+BKoIbZIibjCQWB8EaQfwZ2MQ0cIswWBm4EPW36gkYZqzre9i+n8YFPL6e7K2XfQMyOPQWiSBEhmOWcKJ1RFVSYTSJJEeGJBMFihJ8F3j5NQcOs4A09NtdfUqaXs4pX2LSjiGoRYyCeEyETKOAkp2xq4IXZQoFIwtFZ8ORU9Y058i/APk6Qy5RZwRpepjlnMgOMTIbL3BNYySnNsqABIZYMEZ5QEAisMJbXAH/PCXLG0vb21Ijnj+mb4m5Qz7QIAgUMOUVqgDCbxCYlCJ6MKCj6i3sXynuBCifA7VlI2+sf4kVxlcvUM62CwOIpzLKgUaAgKUHwZFTA5py1bDs/AXyIE+CWbaetqSBi9Jc80y8IDDkFnX0dTWRShCD40bzTX1DkY0DCU+RyR3tTrhR4LtMsCBQQ9UR+tgWNEJERBMdEeRpWnw3cxFPkMEo7k1zeCDhmQBA4UqxPQZhVnKYEwbEynp8/oaAxnrY1ulNWdyzWV4ow7YJAgbJUEfGzbkZjJUNQguBYeOX6eUbOA37IU+B6RWhXbon+dAI9zIAgUKDLVTEos43B4yQnUxcCJ/iRBApDXt8A/CpPgRvySjvKPB3G8JPCzAgCVeiJK4goKLOCqEd8huCxeDKC4Ngo/DiedwCDHCennrZUynhuvcA5KDMiCBTojiogHlRmQcB48qhIre8UtsqZ1IcjBCUIjoUKKwuZ3AB8hOPk4kxoR2msbxRlxgSBBzpdFVBA2jZg0Jw87mS8dxXjfavJu/pIBgyqIEIQHBNRSGJ9AyL/ASjHwSUF2o7COaI8nxkUBKrQYaogSrsRnwNKVuhuhMvYvNVkhS5AcXlGJAYhIgiO09UevRL4HsfBeZR2EyfyijSmLMqMCoKSVAEPWFqfIt4DSlrqY2zeqYz3riCPO2BqNgOgBqwFhDYQqAoAIkqzCTjNedVxB43mtBeRUhbrT4oyo4JAgRLtcHSmiM9BDPWO+Yz1r6HSs4w8KjV+XHzG0Ywo1kDuQQhaVT0VjAHvQUSInTZ/Nd7wciPydmCIY+QiK7QTD89COY8ZFgQKFLUK+JYOGDWOWtcSRvtPo9azhNzEiOaYPOWJiIA1Sp4LCEELSjLhGWfexY3P+RC1pMQ/f+UXeGTXKURWaSphdZZyHfAJjpHLUtqKi/Q1npMjCCKtAdqCA36PGkeldxVj/adS61yEGjsZMD7lR5gKGoIWleXCgu5B/vAn3snKFWtBlN7SCG/8139GVZp6jGYE6jV97XEFTVpT2kWlLIvmwbWcDEEgEOU1UG2ZgBHNyV2RavcyxuafRq3cD2IOHZEdCwURMEYBIWg9uUJXcZwlvbugVgaXsWrBFiKXk+YOoXm8h2I31xRgNbCZY+B6umkfRZ7rKywRZlYQKIIViKUOSEsETBZ1UOld2ehgklLfoeG/ZhwPBYwBawkrzi0qsrDtwGL+5/ZX8MqrPkFWL/CRb76OauKIndJs6unLM7kO+DeOgcsToV10JPqaNAKUGRUECsQCJUlApWkryoKSxl2Mz1vdWFNOit0IiviMEyEyFTQErciIknvHn336N7jl/udRSwrcu/k8Iqu0iiTSVx9z0CSR0g6sl9UKzxBlVlIVVMEYJWg+VShaT9nVOal0MkTMRKWlHsbnncJ43yqyyRXlxo9PB0GxRglalzWKqvCtBy9FBAqR0kpEuRzkHOABfgQnKrSDzPI84+mfrYO/3EMhUqqJUIxaYmc+bJzZlLKtA4YZpx7yFGze2CA7sPAK0r7FZIetKE8nY8AaQAVQgtYkohRjWlWH8bwQeGDWfE2AoC9VZp/MC/O7Bnnri/+O5Qs3cfNdN/Cxb78SmrpZEqhCbNLJjsYLM0chq4MrMLz0Qg6cex2bRq9idE8nkWSYPGUmiIAxoDx1QaBWX6xe/hbwPAnnhZZnhGUqXI3Oxm4GfuY5H+alz/wPyGIuXXUfa7efxZ3rz6cY00xhRmMyimaGgkZzyBKISgysega7z7iWoaUXYYoF/P3SCBixyoxQEAPWKKBND/R6ImQ5GAPFOBwftxNVnqY5pwPr2v5mAF/gOnL6mIVEYGnfLvAOkhKURpnXMYQSND1oJKUgCSBMG59BnuALPQyccs1EwLyA4YVn402EzevYtIpoETAz/MVnYG1zj85yL3gPF505xtLFNUZGHfc+1M14zVCIlLYQFK3R639k0LT6QDDOReqi1ymzlMLHv/NKLjr1Hnq7DvD9e6/jro0XEzmCJlIgIqUgdVABmY6ASck6+tm36ir2nH4tY/PXAGDyFJvVTvrZvzWK0hzeC3Hk+fUbN/Gya/dQLKXgLXf8oJc//MfT2La7SBzCpi0oXBfJkx+fOSdCK6sYXWAyns0sVYiU7667jBv/4QMs6dvND7eeS6VewFklaC5HRsQJdjR5CupJuhaz99RnsWfNsxvPwogqJksApVmMBRGaolqHN7x8F69+yXbILSQODFxx8QF+942GN/3J2WiYU7YHy9N3bNCVwGaegNuxSWll3QvlilKPLvQ5zOaw2bp/KZv2LCWOCCHTAhSwpIgmIBwnfTRgaj0r2HPac9k7ETAHr4kRzRvdSytwTZrR5F7o6fQ8/8r9gEAuNHggt1xx/jCnr6zwwMaOMKdsA6p09S3l6U8aNH1LaWmurNf7nFkvsjpRBM2ioHrYew9RWod8CLQAGBALGECefEUZqCw4g12nP58Dq55GvTz/0PFYi9AmdjSqUIg9pWIOCEdQKERKuehRpU0ErsSLgY/xBJwr0bKMl06vejUzJAjUAwomAhuDLYEpCJGF8bifz5Vfy7xsiFXZVvrzfZT8IGBAYkBoUIW8DjZmdMn57DrzOg6suIIs7sLkSWPA33JUcFYx0pwHEQ8MOR7e0sGpp44Chkc5z/adJbbsLIY5ZTtRno5IHzDI43AgtKrhbs7sGuEMhGkXhIARIOqCeL4Q94DrBAyI0DDEIv5KfwUBYvWsTjdxcf1erqp9k/OT+8HXwAu4AgMrn8aeM17A4NKLyKMSJjsYMJXWPhq0IAIKCCePCIiBf//vFVxwxihLl40DAihp3fHPn1jJnoGIclFpE4GwMk64CPgaj8PFCS2rXOFpCDFtJvdCmoM1tNLdRMHhx2LdUFoO8TzBRICC6mGvgAARk3IMD8VruH+iPtXxEi6r3cWra//N6kUR209/IQMLz8Xb+NEV5XbgDJMUkJM/l3xoU5mff/u5vO76XaxeMc7wcMz/3rKI2+7qDSHTbhSTW572hEGTW1qWy/Q6lfa7TqYUJ5yxZBv7Ruazf7SHglOUoNnUgzFQPkUoLwOJQD1ozo8kQKwQA5lEfKP8NO6YqCsXJTx3YY0uWyfNarQNBWMUEVClKQqxsmlHiT/8p1MpxlBPwQgUC0r7CbzRFwB/wuNw3mirzmfmqeEStL06md6OYd792j/kmnNuY/2u0/id/3wXD2w/vQWu9g4hYwvQebpQWACaN+opMUBJIQe+sTlm+5DwE+emLOrISHKhHRx+dNZMkdOJAq9CqaCI0KYChQuNyjJgR9tcqpkZvUyURbSRegrPPe+bXHPBVyEtcdqp9/CKKz/N2m2/gSIIStCkkClC95kQzQPNmBYWsBY2DkV8+Ae9vP6CIRZ3tk/YWAMitAQjStsLenOjzwD+i6O43CgtyculiDraiAiMVLtALbgEUMaqXShB0yiYCLrOEKI+0IxpV7Cwa8zysR/2cONFQ/QVPKmn5VmryPQNaIJAQC5/3KABoQWJiD6DNlOI4Btrr+bfv/RLvOiyL/DDTRfxn996Nc4QupkmUYXOU4S4HzRjxhQsbBtxfOahbl53/hBGwCstSxWcDUdV0ysQ1SuACEg5jBNVWo0aehQuF23Db8VTx99+8Rf4l5t+niQXjEBkFeVkCzSHwgIoLQbNmXGxhR/ujbljR4lrVlWoZ0IrsyFoplkgcImKLDx6TuMQodWo5yKDLqQNGVEKDlSF2CoAStAMxkF5pYAAnhkngBG4bUsH5y6s013w5J6WJQLGMG2CQKEL1UseGzSqtJoCPD0BEdqXiBI0j+ZQXCJEXaCek8YZ2Fsx3LO7yAvXjJHkglfwKqiC0jrksK8LFmG6BMHVwOc4jKMFiXARylMTBArGQmERIJx0kYE7dpQpO09sob+c0V/K6Yg8CmReaAUi4CzTKghUuIijOBVai5euOnq28NQFgSkz2c3kzVkbHqwa/vfBbkTACI2gOXN+nYsX11jenTbCxitNZ4yiTJ8gEOV0PPOB/UxxktNajC4BziAIjpVyiDB1xYyABTxNYQQQUCZr77hlx1iZ7+8ocdXKKs9ePUZktHndjYaOZsYEq3CsOiJocLQUUTlPVQsEwZNQD3gQe7AO/Zjmk+U6QQyop6nksC7HArVc+PL6MttHHK88e4SuQt6UsFFABKxTQABlmgSBQeVC4C6mOFRoJap6OcGTCQEjU7cu9wuuA0x02LclVyAZVGwBUFqOFbBucg069T381PlDlCJP7oVmsAZUmV5BoHoZ8P6W3ToT5QIVguAxNAfbAR0rIZ4vGMckZZLQUFoqAGhOyyo6WLc/4qYNnbz8rBF8E3JRRDDWoEy7ILigZbfOjJcONXoqjyMIIRP3Q9fpgi3/iEsxDaC0vNjC7TtKnLewxhn9yUm8I01QY1HxdMkoTroAwzQKghWozAMGWu7oLDe6WmApRwtCyPRBz9mCONCMJ6e0BSNQz+FbWztYMy89aQGDeopje+k58DDl8Tob7fOoaBGDMk2CYKEYPR24HcCJUVpFlLIyjehGaQgC1anr/U8TJALNmVUiA1uGI/aMWRZ15swIEVQs4jNKwzvpPLCB0uhOnE9ItA8RBWU6BUExyzn10aDJclqGWDkdVYLgUR6KS8B1gubMOiIwlghbhmOWd1fImT4qBhWL8QkdQzvoPPAIhfF9GJ/jjWuU9YrBo0yvIBAjpzHFiRFaRS6cI8qkIFAwMRQXCeqZlQTIFfZXLF4B4cSJwRuDTauNgOkY2Eihsh9UUWMbAQOgCE4yLDkoIEybIDCiZzHFGVFahnI2QTBFPcTdgikwq1mBSmLIvOCsnlAHgxhsUqFraAudBzYS14ZQpmYzwmM0gkY8yjQLAuVsFRyQOaU1uFzKip7qDUETeS8T1TpXyLvyoQcvZzPlqVNjUQxRbZjOwc10TJSrjwHgjeOJKIIjx+CZAUGw0ov0AvudF6EVpJaVRukmaAqvQq0GnWWlsytj/1CEVyjGStMoiAMM4Jm1vEIpUqwoelwbZAaAuDpE54FNlIe24NIKKgY1lmNhJMdJxgwIgk6Tc2ojaExOSxDR1UAHJ13gPYDyhpfv5seevZeuUsb23UXe898ruWNtV1PDRhVQZjUR6C9lWAM5P5oaB+opjO2j6+AG2fAObF5DZWr+cpxiSZgBQVCY+vv6HU5EaQUCKxQsJ11QT4W3vHYrv/j6zUwSVq8a44IzR/nld57LnQ80L2x8Cujs7mY6ImV5T0rmBTH6I1aUc0oju+gcmAwYyTMwBm8inqqCpCjTLwgUVgO0zowmlZVprIhyEgVpJpyytMZrfmw3qEBqmGTo7k14/Yt3cPeDZ+IVjHByGchGFc0FDKDMOpmH1X0Zyzszcg/OPP6KsvUppeFtdB1YT2FsL+Iz1FjUOk6UI2O6BYEA3rMSwKmnJWSOlaKcZEGWw8oldXq7MsiFI8nEz9Xo6coZHXcYq5xMYiAbm6yoB1SZVRQwwFUrKjirJLkcETDeTq4ol4d3NI7I4vEDgJ8MGOOYLpGkTLcgUMAalgM4a2gB4lR0GcpJFlihMfiv1gylTg+ewygDQxGVqsUITaE5VHcqUY/Mutvs6xlcuqTOuQvqpF4A8DZqlEvG6TmwlY7BLcTVAfTR4b9jmp3kZYBwglBPQBWcg2KsiDBrKSxFKDkVmk6ML5PLYk66IIqUdZvLfP3OebzouTvBOfCAU/DCp29dRK0ulIpKM4iB+j6o90NxMfiMWaGew4runOvPGEWA3MSoGLoHN7Fo407qG8YoZSMogjeOmeQkZ+YF1bpw5uoq11wySKGY8+AjnXzr3j6YepxgllqoaIdTlGarDkix2MVSMZxkgchkvfu9p5Dm8OwrB+gqerbvjPnwp5bzpW/Np1hQmkYAhdENiikIUR9oDihtySskOazqyXj1+SN0dTqSXOjcv55F629h4ZavMbLvPHZkF854wAAIEEnGzApqdeG6Zwzwx7+0nr7+KgA+t/zXF5bwp+87FVUQYTZaVEil7Aqp0Gx5Kn0q2iMEzeCsMjQS8bt/dwanrajS1ZGxY0+BHftiSoUWaO0FfAIjDygda4TiQsCAekBpeQqoQuohtvC0FXWuOzOh23lKOx5iybovMW/7nZjaCDgldzGaGyBnmoX15ibIcmHZooTf/7kN9PXXIHEAGKf85Et2sHZjF5/48kLKRWUWKuYq/S5XodmiBSxTxRA0jXOKKjy8pYRXcJaW+j++GPAJjD6kJAegtERw3YCACCBMqyQFryCcGCOTVYqU8+alXLLSc3b3CL0772X+uluYt+MuSKtgY4hKIAknWyQpCDMkSFK49OxhFiyoQ2p5VCYQw9UXD/DpWxfgVTCizDZZzDKXxTSdKIsImk4ECrHSsgwNtT1Q36+4TiZKMDGIZVqoghG48oIaXR0e709s0aJgPf2dwpI+Yb4ZZuHOO5l3+0307F4LeQKu0AiYZookm8FLNQNVsJYnZI1iBJTZyaALnUFpNoWFBMExEgsopCOQDiso00YVIgfXvniMJfMzslxO6A6y3BZw4weYt/l7LHz4Zsr714PPwcbgirSCiJRg5hRiuOehLoYGY3r765AYGqwCyvfu76Val7Y9OvMqpBkgEFsQUQ6nqgucqtJsgixUjkMQCIgw7VTBRAoGqpkhzzluOvVdL8WRvSzcfBuLHrmF0uBmwICNwDlahU51NJEoiiBo697Fl4AIFCMQ0baagW7eUeQvPria3/+FDZQ6EiYJX7x1CZ+6ZRHFuH1DxpmcS864jyQp8sPtZ4OCCIeRBQ4kdDRBMAWFOAJrAeW4eBujYhoPWC7a8DUWTlQ8uhtEwBVpRYpgG0GTkmhMK8q9UIrrXHfhbVSTIt966Kq2m2cUC8r/3rKQrbtKPPfKA8RFz9p1nXzl2wtIMmmEUbtRBMj5rZf9Ba+6+uNkueNvPverfOjrr8VZEJQpCwwtwAvzaAFBoEAhVkSUYyIG7woTVaRzYCNrbn8PF375d1l+z38Sj+8DVwAb08ocOZFkKK3He8GahD985bv48zf8Cn//c2/iTS/8F9KMtlOMlbse6OLd71nN2/7xVP7nqwvJPW0ZMgB5Dsv79/LyKz4DanBRwque/t/0livknkkCqvQ6VZpOlE6EpgsCVaEQ+R89nBUhtwWMz+je+wBLHvoK87bdga0NgW0M+NvmP6+TqaBRQGgpaQ5nLNrNtRfcArlDTMZLLv8c//7V/0s9LSCibTav0YmaHbsXIjBaLbN/tJ8lS9aDydk1uIRa6jBMUUAoO4QmE2PQDqX5gkAV4lgx5skDxmZ1+rd9n8WP3Dy5opxUplaUy7QbQ44lR2k91sC+kXls3HsKZ53+PQAe2nEmlSTGGaVdCe3PGmVgrIff/eg7ef1zPkStXubfbv55amlMZJXDFB1NJlBSKNMigiCOwIg+ZoPM2xiXjLNg27dY/PBN9O66D/LkUAfTpiweR9a6DxOPd/JHn/wDXnfNR6kmZT74tRtRFUBpriCyyh3rL+LeTRfhFTIPBacohwiUndBcAkWFDlpAEKhCIVKMARTUOHIbE9cGGwP+JetuomP/w+CzyYBxRdqZIhjxWPEorSl2yg+3nslvfPhtKFBwEFtFCVrlfx+vgsjke+UxSo4mU7QAlFrlvFoEQAnmcNDECs6R2YjC6B7mb/oWi9Z/jfLABkDAxuAcs4WhETQt/zezyAkCQKuFTGBEeRKFVgiaSJC4Fb5l0hqmtkAEZxQlmItBExUs5epeFjz8NRZMBExhZCeIAVdkNjIohpxWJyhtKYgdTScRUKCJ0ly45uzvc8MVn2HX/uV88OuvZ6xWxhqCOSazcNaBW7ngy/+AHRoEE4ErMnsJIh5BUYJgRkSOJhOIgJgmSTJhzaJt/PXP/Bod3XvBZhSiOn/26bdgjRLMLWpgyeiDWLsbXC+znQIGj8UTBDMkNjRbk4Mm97Codw8dPXvx1R5IC5y9/CGMIZhjFCESiF0GJmKuEJTIJAhBMCMiQ/NZwNEkkYWHdpzO/euejimNkGcFPvv9G8g9wRwUCZRNDRDmCgVKUiMIZog1NJmCaf6efg9vfv/f8Jvv/1ve+I8f4LN3Xk/BKcEcXAQwSperg86loBFKUscQBDPCOppMwLTCQ2EHRnv57B3XYQRiByIEc4wCkcnocFVQw9whlEwVEYJgJhhH85lWeQLZWYK5HjSS02Frc6yjgYIkCMz0VwUEIWjCtT9B4CSnaOqQC8dFOUQf53OD8BjKkUQopoZC6ojE84QElEkqAPrYzwIKqChPToglQVAUYZoFgTiCIGhQwJFRliqoHBkEhz4fWQgIYISalamC1CmpUfKp8gdLFDUKoiQGcgEz9T4VsCi5y/lObZBNtW3E3gNgVbC5AcB4wXmDUcH6g2UO/djUZ+uFKDdEmcUdfM0doqACioKAF300hIxRSmSIF1QABESZLkHgaD5PEDSjiVYQBXJQD5qDoYDzOVVxJNaS2cmQGImVfSXYV1b2d+SMFXOqsSePcnKXkUQ5SexJo4xarNScklgltZ7MKrmdChvjwSgCgGJQhElGPE48t4449td3gXiekBfIDW6qotzi/KHPcWYppG6ibKNKqaNUjykljnI9oqtaaFR3NaazbqknVTSuQx4juWASAQU1gAGVqfcCoByHIPBy0Us9TXY5cAfTLQhUjggSD6iZLBHAebLOAbRnN653F65zP/0927h26acYLtXY36GMFjOSQoZzKc5mWJtOdSegoqiAoFgFg2JRppoWBBAVBEBpECbpobA7QiQ5Xxw+n021hSA5T0oO/0OPei+H/7wCwmFnaeAFUcGoNDqfqNJFPj4fV+0iGu8hGp2HrXQTjfcRjfbhKj1EI/3YpAAK4gEFODqIlCA4StoKQXMpcCdB8BSJCuoBD6qThUIeQVauYnp2E3Xtw3bvxS7YSLz0IQp92ykVR+gojBAVhzGFCiauYiQn80UiBTNVqIAeHg7CTIkl40vD57GpthgkY8Yc3ZmIB+NB/KH3KpAWkaSAyQrYtIAb7yUeWExxcDHx4BKikXlElV5cpQs31odNQAVo1KH3agCUYE6qt0LQXAzczY8UBALKZOVANvVSBDqHiUpDaP827Mr7KC9eR0fXHsqd+3A9uxvdSsHVKOIxKqgaUEER8FPvMYcCpUkKJuNLQ+excSpomk50KnwA/NRnPRRGWYSt9GCrnUQHQ2hwEcV9KylNVGFwSePHG1W3iIJaUAMqc+gYLqi2QtBcANwFOILgKOIFMvAecgsaK6Y4Sr70YeIV99HZu43SvK24JQ9T7N1BVzxKwSYgHgGMN6h34C2qgkdoYY2g+crQuayvLQHJaHmHh47kIBw6R0sj4pEFFBrdz2KK+1dQ2rOK4oEVuGoHkllMBmqYCiAlmJVGWyFozgLuJHz5WaACGaiCB0Qg7R6Fxesp9m+iOBEm8cp76Vn4CD3lfdjiGNYmRCqQOdQ7vBoUoV0VJOOmkXN4pLoEJKetiYLJD1UeIUkRk5Qp7l9KefepFPespjiwbOLzcqKxTlAmayp8VJS2Fww4mk1JEeohaOYgL6Cg+WRlRWDRdgrzdhCvvpPO075Lb/8GCr27iMqDlCTD5g4/FShkEaQxGS0pfO+KCuSuUQ2iqE3Jy0OMrz7A+Jp7AEEqXVPHbkvo2H4GHdvOojjxPh5eiK2aqW4HkDbteoKkFTqalcD3gCUEs5yABzLIPeRlj+3eg5x6Nx2n3E7vwocpLn2Acu8OOkyCqIC3jdKJ8gizXUEybhk5i4eqy0By5gSTH7aIoKBgR+dT3L+M0t5T6Nx6Dh07zsCN9+CqEQqoa6MFg2Cro9lEE1TqBLOTCqTgFdSBdowhp9xF54r76FjzXbpW3k1v+QDW1bCAZDE+dXgi5iIFDMqc4m2jDpeXhxk/ZT/jp/6A/Zd/HlProLTnFDq3nUV55xl0bD+LaLQbyQUEvANEaUlB6mg2lQSoE8wScsQDkHkBdPWDlFffQ/ncm5i/9Id09OxqrBTH3qBZAX/wtd5BTgAg4W+YR4WP4uMq46fcx/iauyEpNVapO3aeRtfGi+nYfnqj87F1QQ2TZQGUlhDUHU0nVdBx2legAgpkkCn4vmGi+ZspnPtV+k+/je5l99PRtZeCF/zUBpjWOsgQfrQQNIGACqQxEIN4su79DPfuYfi8b2LGeynuW9E4Yut+5DJKe1cRjXaCCGpb4IgtqDiaTJWawChCOwoBk0BmQDoqmDV3MO/8r9B12rfoXfQwHa6KKJDF+EawBNNwnXmgBvKD5QAa3U5l5QNUVq1l7zM+RXEiaDq2nU3PI5fSsfVcXKWMeEGjJm2xBVVHk4moIlRQ2kAgXvAZKJCX69izv0fvWd+k57yvMH/eBuLiKDaL8AfDJS8TnNyts3DMBrVFm6ktXc+BS25q3GLQs/5SujZdSOeW83DjRZCT+dxOIFBxQvPFhtFaDkLQumuqoBkkJcWdeg+dl36KBWd+na4F6ykXRjBpgdw7tNZJRvDUCQYFlOApyqLJEiXp38m+ieDZd8XnKexfTvdE6PSuu7KxUOCqFu9m+o62wAvjcuHLPE2n/JvAz9F6QsDUIY3ALNxG8cIv0H/el+k75Xa641HwDs0ivFqmRxBLzu3jp3DX2GoQzzQJxIPNwWaQxo2g6XnoSvoefAaFgcVIBj4KgTMTBD7ojNJ0CntoHUEm5DloZ43okptYfP5EuJzzVXo792BRNC2Q1ztpG+HoLFADmXm006mseIDKyrXsuep/6N54EX1rr6Z7/WW4aoQ3oE6ZHoHCPqe0At0DQhMFXtAMvIJfvIPOi77I/Cs+2lhHLkZVSErkB4tgJikgBDP/bFfh0UWCofO/ztDZ36G4dzXz7ns2vQ9dSXHfYhBQd+ILBIHucaA0ncouhGYJAZNAVlSiM+6m7+kfZdE5N9HTvwmXOfI8Jq91cvIERjwnSaAGkhKIUlu8kZ3L1rH3Gf9L9yNX0H/v8+ncdiYmOaGNtUDNbocamk2F3YJyEgVe8An4jhR74VdZds0HWXjm1+hwFchj/Jwb6oejs3Cha9SorGOYgUu/yMAFtza21frveR49D18xeawWh8A5XiLsdSI0XVHYU1e8giGYWbngM8g7a5Se/jn6n/FhFq2+nZKtomk5zF5C0AS5myxRRs+4g9E1dzeuvOm/+zp6H3wG0VgBHx3renSQ5exxWU7TeWHYGPYDCwlmjgc/byelSz7L4qf/J/1L7ydWJc+K5HkHrSEwBK3zQHIRUMZXPNCovU/7DP33PJ++tc/AjfeBEDy5cTE6+P8BW01E00mieO8AAAAASUVORK5CYII=) no-repeat 150% 100%;
      background-color: #2238b3;
      background-size: 205px;
      background-blend-mode: luminosity;
    }
    .leftnav__header__title {
      font-family: var(--text-font-family);
      font-size: var(--title-font-size);
      line-height: var(--title-line-height);
      font-weight: 300;
      color: #fff;
      margin: 0;
      padding: 0;
    }
    .leftnav__header__version {
      color: #aab3ed;
      font-family: var(--text-font-family);
      font-size: var(--body-font-size);
      line-height: var(--body-line-height);
    }
    @media screen and (max-width: 964px) {
      .lh-leftnav {
        display: none;
      }
    }
    @media print {
      .lh-leftnav {
        display: none;
      }
    }
  </style>
  <nav class="lh-leftnav">
    <div class="leftnav__header">
      <h1 class="leftnav__header__title">Lighthouse</h1>
      <div class="leftnav__header__version">Version: 2.9.3</div>
    </div>
    <template id="tmpl-lh-leftnav__items">
      <a href="#" class="lh-leftnav__item">
        <span class="leftnav-item__category"><!-- fill me --></span>
        <span class="leftnav-item__score"><!-- fill me --></span>
      </a>
    </template>
  <a href="#performance" class="lh-leftnav__item">
        <span class="leftnav-item__category">Performance</span>
        <span class="leftnav-item__score lh-score__value--pass">83</span>
      </a><a href="#pwa" class="lh-leftnav__item">
        <span class="leftnav-item__category">Progressive Web App</span>
        <span class="leftnav-item__score lh-score__value--pass">100</span>
      </a><a href="#accessibility" class="lh-leftnav__item">
        <span class="leftnav-item__category">Accessibility</span>
        <span class="leftnav-item__score lh-score__value--pass">97</span>
      </a><a href="#best-practices" class="lh-leftnav__item">
        <span class="leftnav-item__category">Best Practices</span>
        <span class="leftnav-item__score lh-score__value--pass">100</span>
      </a><a href="#seo" class="lh-leftnav__item">
        <span class="leftnav-item__category">SEO</span>
        <span class="leftnav-item__score lh-score__value--pass">89</span>
      </a></nav>
<div class="lh-report"><div></div><div class="lh-scores-header">
  <style>
    .lh-gauge {
      --circle-size: calc(2.5 * var(--header-font-size));
      --circle-size-half: calc(var(--circle-size) / 2);
      --circle-background: #ccc;
      --circle-border-width: 2px;
      --inset-size: calc(var(--circle-size) - 2 * var(--circle-border-width));
      --inset-color: #fff;
      --transition-length: 1s;
      width: var(--circle-size);
      height: var(--circle-size);
      background-color: var(--circle-background);
      border-radius: 50%;
    }
    .lh-gauge--pass {
      --circle-color: var(--pass-color);
      color: var(--circle-color);
    }
    .lh-gauge--average {
      --circle-color: var(--average-color);
      color: var(--circle-color);
    }
    .lh-gauge--fail {
      --circle-color: var(--fail-color);
      color: var(--circle-color);
    }
    .lh-gauge__mask,
    .lh-gauge__fill {
      width: var(--circle-size);
      height: var(--circle-size);
      position: absolute;
      transition: transform var(--transition-length);
      border-radius: 50%;
    }
    .lh-gauge__mask {
      clip: rect(0px, var(--circle-size), var(--circle-size), var(--circle-size-half));
    }
    .lh-gauge__mask .lh-gauge__fill {
      clip: rect(0px, var(--circle-size-half), var(--circle-size), 0px);
      background-color: var(--circle-color);
      backface-visibility: hidden;
    }
    .lh-gauge__percentage {
      --spacer: calc((var(--circle-size) - var(--inset-size)) / 2);
      width: var(--inset-size);
      height: var(--inset-size);
      position: absolute;
      margin-left: var(--spacer);
      margin-top: var(--spacer);
      background-color: var(--inset-color);
      border-radius: inherit;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: var(--header-font-size);
    }
    .lh-gauge__wrapper {
      display: inline-flex;
      align-items: center;
      flex-direction: column;
      text-decoration: none;
      color: inherit;
      flex: 1;
      min-width: auto;
      position: relative;
    }
    .lh-scores-header .lh-gauge__wrapper {
      width: calc(10.5 * var(--body-font-size));
    }
    .lh-gauge__label {
      font-size: var(--body-font-size);
      line-height: var(--body-line-height);
      margin-top: calc(0.5 * var(--body-line-height));
      text-align: center;
    }
  </style>
  <a href="#performance" class="lh-gauge__wrapper">
    <div class="lh-gauge lh-gauge--pass" data-progress="83">
      <div class="lh-gauge__circle">
        <div class="lh-gauge__mask lh-gauge__mask--full" style="transform: rotate(149deg);">
          <div class="lh-gauge__fill" style="transform: rotate(149deg);"></div>
        </div>
        <div class="lh-gauge__mask lh-gauge__mask--half">
          <div class="lh-gauge__fill" style="transform: rotate(149deg);"></div>
          <div class="lh-gauge__fill lh-gauge__fill--fix" style="transform: rotate(298deg);"></div>
        </div>
      </div>
      <div class="lh-gauge__percentage">83</div>
    </div>
    <div class="lh-gauge__label">Performance</div>
  </a>

  
  <a href="#pwa" class="lh-gauge__wrapper">
    <div class="lh-gauge lh-gauge--pass" data-progress="100">
      <div class="lh-gauge__circle">
        <div class="lh-gauge__mask lh-gauge__mask--full" style="transform: rotate(180deg);">
          <div class="lh-gauge__fill" style="transform: rotate(180deg);"></div>
        </div>
        <div class="lh-gauge__mask lh-gauge__mask--half">
          <div class="lh-gauge__fill" style="transform: rotate(180deg);"></div>
          <div class="lh-gauge__fill lh-gauge__fill--fix" style="transform: rotate(360deg);"></div>
        </div>
      </div>
      <div class="lh-gauge__percentage">100</div>
    </div>
    <div class="lh-gauge__label">Progressive Web App</div>
  </a>

  
  <a href="#accessibility" class="lh-gauge__wrapper">
    <div class="lh-gauge lh-gauge--pass" data-progress="97">
      <div class="lh-gauge__circle">
        <div class="lh-gauge__mask lh-gauge__mask--full" style="transform: rotate(174deg);">
          <div class="lh-gauge__fill" style="transform: rotate(174deg);"></div>
        </div>
        <div class="lh-gauge__mask lh-gauge__mask--half">
          <div class="lh-gauge__fill" style="transform: rotate(174deg);"></div>
          <div class="lh-gauge__fill lh-gauge__fill--fix" style="transform: rotate(348deg);"></div>
        </div>
      </div>
      <div class="lh-gauge__percentage">97</div>
    </div>
    <div class="lh-gauge__label">Accessibility</div>
  </a>

  
  <a href="#best-practices" class="lh-gauge__wrapper">
    <div class="lh-gauge lh-gauge--pass" data-progress="100">
      <div class="lh-gauge__circle">
        <div class="lh-gauge__mask lh-gauge__mask--full" style="transform: rotate(180deg);">
          <div class="lh-gauge__fill" style="transform: rotate(180deg);"></div>
        </div>
        <div class="lh-gauge__mask lh-gauge__mask--half">
          <div class="lh-gauge__fill" style="transform: rotate(180deg);"></div>
          <div class="lh-gauge__fill lh-gauge__fill--fix" style="transform: rotate(360deg);"></div>
        </div>
      </div>
      <div class="lh-gauge__percentage">100</div>
    </div>
    <div class="lh-gauge__label">Best Practices</div>
  </a>

  
  <a href="#seo" class="lh-gauge__wrapper">
    <div class="lh-gauge lh-gauge--pass" data-progress="89">
      <div class="lh-gauge__circle">
        <div class="lh-gauge__mask lh-gauge__mask--full" style="transform: rotate(160deg);">
          <div class="lh-gauge__fill" style="transform: rotate(160deg);"></div>
        </div>
        <div class="lh-gauge__mask lh-gauge__mask--half">
          <div class="lh-gauge__fill" style="transform: rotate(160deg);"></div>
          <div class="lh-gauge__fill lh-gauge__fill--fix" style="transform: rotate(320deg);"></div>
        </div>
      </div>
      <div class="lh-gauge__percentage">89</div>
    </div>
    <div class="lh-gauge__label">SEO</div>
  </a>
</div><div class="lh-categories"><div class="lh-category"><span class="lh-permalink" id="performance"></span>
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--numeric">83</div>
    <div class="lh-score__gauge">
  
  <a href="#performance" class="lh-gauge__wrapper">
    <div class="lh-gauge lh-gauge--pass" data-progress="83">
      <div class="lh-gauge__circle">
        <div class="lh-gauge__mask lh-gauge__mask--full" style="transform: rotate(149deg);">
          <div class="lh-gauge__fill" style="transform: rotate(149deg);"></div>
        </div>
        <div class="lh-gauge__mask lh-gauge__mask--half">
          <div class="lh-gauge__fill" style="transform: rotate(149deg);"></div>
          <div class="lh-gauge__fill lh-gauge__fill--fix" style="transform: rotate(298deg);"></div>
        </div>
      </div>
      <div class="lh-gauge__percentage">83</div>
    </div>
    <div class="lh-gauge__label">Performance</div>
  </a>
</div>
    <div class="lh-score__header">
      <div class="lh-score__snippet">
        <span class="lh-score__title"><!-- fill me --><span>Performance</span></span>
      </div>
      <div class="lh-score__description"><!-- fill me --><span>These encapsulate your web app's current performance and opportunities to improve it.</span></div>
    </div>
  </div>
<div class="lh-audit-group"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">Metrics</div><div class="lh-toggle-arrow   lh-toggle-arrow-unexpandable" title="See audits"></div></summary><div class="lh-audit-group__description"><span>These metrics encapsulate your web app's performance across a number of dimensions.</span></div><div class="lh-timeline-container"><div class="lh-timeline"><div class="lh-timeline-metric lh-timeline-metric--pass">
    <div class="lh-timeline-metric__sparkline">
      <div class="lh-sparkline__bar" style="width: 39.7596%;"></div>
    </div>
    <div class="lh-timeline-metric__header">
      <div class="lh-timeline-metric__value">1,790&nbsp;ms</div>
      <details class="lh-timeline-metric__details lh-expandable-details">
        <summary class="lh-timeline-metric__summary lh-expandable-details__summary">
          <span class="lh-timeline-metric__title">First meaningful paint</span>
          <div class="lh-toggle-arrow" title="See audits"></div>
        </summary>
        <div class="lh-timeline-metric__description"><!-- fill me --><span>First meaningful paint measures when the primary content of a page is visible. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/first-meaningful-paint">Learn more</a>.</span></div>
      </details>
    </div>
  </div><div class="lh-timeline-metric lh-timeline-metric--pass">
    <div class="lh-timeline-metric__sparkline">
      <div class="lh-sparkline__bar" style="width: 100%;"></div>
    </div>
    <div class="lh-timeline-metric__header">
      <div class="lh-timeline-metric__value">4,500&nbsp;ms</div>
      <details class="lh-timeline-metric__details lh-expandable-details">
        <summary class="lh-timeline-metric__summary lh-expandable-details__summary">
          <span class="lh-timeline-metric__title">First Interactive (beta)</span>
          <div class="lh-toggle-arrow" title="See audits"></div>
        </summary>
        <div class="lh-timeline-metric__description"><!-- fill me --><span>First Interactive marks the time at which the page is minimally interactive. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/first-interactive">Learn more</a>.</span></div>
      </details>
    </div>
  </div><div class="lh-timeline-metric lh-timeline-metric--pass">
    <div class="lh-timeline-metric__sparkline">
      <div class="lh-sparkline__bar" style="width: 100%;"></div>
    </div>
    <div class="lh-timeline-metric__header">
      <div class="lh-timeline-metric__value">4,500&nbsp;ms</div>
      <details class="lh-timeline-metric__details lh-expandable-details">
        <summary class="lh-timeline-metric__summary lh-expandable-details__summary">
          <span class="lh-timeline-metric__title">Consistently Interactive (beta)</span>
          <div class="lh-toggle-arrow" title="See audits"></div>
        </summary>
        <div class="lh-timeline-metric__description"><!-- fill me --><span>Consistently Interactive marks the time at which the page is fully interactive. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/consistently-interactive">Learn more</a>.</span></div>
      </details>
    </div>
  </div></div></div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--fail lh-score__value--numeric">0</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Perceptual Speed Index</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Speed Index shows how quickly the contents of a page are visibly populated. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/speed-index">Learn more</a>.</span></div>
    </details>
  </div>
<div class="lh-debug">Audit error: Images have different sizes!</div></div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--numeric">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Estimated Input Latency:  16&nbsp;ms</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>The score above is an estimate of how long your app takes to respond to user input, in milliseconds. There is a 90% probability that a user encounters this amount of latency, or less. 10% of the time a user can expect additional latency. If your latency is higher than 50 ms, users may perceive your app as laggy. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/estimated-input-latency">Learn more</a>.</span></div>
    </details>
  </div>
</div></div><div class="lh-audit-group"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">Opportunities</div><div class="lh-toggle-arrow   lh-toggle-arrow-unexpandable" title="See audits"></div></summary><div class="lh-audit-group__description"><span>These are opportunities to speed up your application by optimizing the following resources.</span></div><details class="lh-perf-hint lh-perf-hint--fail lh-expandable-details"><summary class="lh-perf-hint__summary lh-expandable-details__summary"><div class="lh-perf-hint__title">Offscreen images</div><div class="lh-toggle-arrow" title="See resources"></div><div class="lh-perf-hint__sparkline" title="Potential savings of 545&nbsp;KB (~3,200&nbsp;ms)"><div class="lh-sparkline"><div class="lh-sparkline__bar" style="width: 80%;"></div></div></div><div class="lh-perf-hint__stats" title="Potential savings of 545&nbsp;KB (~3,200&nbsp;ms)"><div class="lh-perf-hint__primary-stat">3,200&nbsp;ms</div><div class="lh-perf-hint__secondary-stat">545 KB</div></div></summary><div class="lh-perf-hint__description"><span>Consider lazy-loading offscreen and hidden images to improve page load speed and time to interactive. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/offscreen-images">Learn more</a>.</span></div><details class="lh-details" open=""><summary>View Details</summary><table class="lh-table"><thead><tr><th class="lh-table-column--thumbnail"><div class="lh-text"></div></th><th class="lh-table-column--url"><div class="lh-text">URL</div></th><th class="lh-table-column--text"><div class="lh-text">Original</div></th><th class="lh-table-column--text"><div class="lh-text">Potential Savings</div></th></tr></thead><tbody><tr><td class="lh-table-column--thumbnail"><img class="lh-thumbnail" src="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&amp;token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c" alt="" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&amp;token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c"></td><td class="lh-table-column--url"><div class="lh-text__url" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&amp;token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c"><div class="lh-text">…o/2018-05-06T06%3A46%3A01.738Z.png?alt=…</div><div class="lh-text lh-text__url-host">(firebasestorage.googleapis.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">154&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">154&nbsp;KB (100%)</div></td></tr><tr><td class="lh-table-column--thumbnail"><img class="lh-thumbnail" src="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&amp;token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0" alt="" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&amp;token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0"></td><td class="lh-table-column--url"><div class="lh-text__url" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&amp;token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0"><div class="lh-text">…o/2018-05-06T06%3A44%3A20.265Z.png?alt=…</div><div class="lh-text lh-text__url-host">(firebasestorage.googleapis.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">151&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">151&nbsp;KB (100%)</div></td></tr><tr><td class="lh-table-column--thumbnail"><img class="lh-thumbnail" src="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&amp;token=60c2ac2a-de60-4ebc-b970-70264d96a80b" alt="" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&amp;token=60c2ac2a-de60-4ebc-b970-70264d96a80b"></td><td class="lh-table-column--url"><div class="lh-text__url" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&amp;token=60c2ac2a-de60-4ebc-b970-70264d96a80b"><div class="lh-text">…o/2018-05-06T06%3A45%3A15.468Z.png?alt=…</div><div class="lh-text lh-text__url-host">(firebasestorage.googleapis.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">133&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">133&nbsp;KB (100%)</div></td></tr><tr><td class="lh-table-column--thumbnail"><img class="lh-thumbnail" src="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&amp;token=d0181e98-3ea9-499b-865e-8cec92fa1e33" alt="" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&amp;token=d0181e98-3ea9-499b-865e-8cec92fa1e33"></td><td class="lh-table-column--url"><div class="lh-text__url" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&amp;token=d0181e98-3ea9-499b-865e-8cec92fa1e33"><div class="lh-text">…o/2018-05-06T06%3A43%3A05.377Z.png?alt=…</div><div class="lh-text lh-text__url-host">(firebasestorage.googleapis.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">106&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">106&nbsp;KB (100%)</div></td></tr></tbody></table></details></details><details class="lh-perf-hint lh-perf-hint--fail lh-expandable-details"><summary class="lh-perf-hint__summary lh-expandable-details__summary"><div class="lh-perf-hint__title">Properly size images</div><div class="lh-toggle-arrow" title="See resources"></div><div class="lh-perf-hint__sparkline" title="Potential savings of 489&nbsp;KB (~2,870&nbsp;ms)"><div class="lh-sparkline"><div class="lh-sparkline__bar" style="width: 71.75%;"></div></div></div><div class="lh-perf-hint__stats" title="Potential savings of 489&nbsp;KB (~2,870&nbsp;ms)"><div class="lh-perf-hint__primary-stat">2,870&nbsp;ms</div><div class="lh-perf-hint__secondary-stat">489 KB</div></div></summary><div class="lh-perf-hint__description"><span>Serve images that are appropriately-sized to save cellular data and improve load time. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/oversized-images">Learn more</a>.</span></div><details class="lh-details" open=""><summary>View Details</summary><table class="lh-table"><thead><tr><th class="lh-table-column--thumbnail"><div class="lh-text"></div></th><th class="lh-table-column--url"><div class="lh-text">URL</div></th><th class="lh-table-column--text"><div class="lh-text">Original</div></th><th class="lh-table-column--text"><div class="lh-text">Potential Savings</div></th></tr></thead><tbody><tr><td class="lh-table-column--thumbnail"><img class="lh-thumbnail" src="https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png" alt="" title="https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png"></td><td class="lh-table-column--url"><div class="lh-text__url" title="https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png"><div class="lh-text">…images/pwa.png</div><div class="lh-text lh-text__url-host">(facebookfeed-neel.firebaseapp.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">285&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">202&nbsp;KB (71%)</div></td></tr><tr><td class="lh-table-column--thumbnail"><img class="lh-thumbnail" src="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A32%3A53.884Z.png?alt=media&amp;token=aca0478e-23b6-45d9-90d7-594641c37b77" alt="" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A32%3A53.884Z.png?alt=media&amp;token=aca0478e-23b6-45d9-90d7-594641c37b77"></td><td class="lh-table-column--url"><div class="lh-text__url" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A32%3A53.884Z.png?alt=media&amp;token=aca0478e-23b6-45d9-90d7-594641c37b77"><div class="lh-text">…o/2018-05-06T06%3A32%3A53.884Z.png?alt=…</div><div class="lh-text lh-text__url-host">(firebasestorage.googleapis.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">210&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">59&nbsp;KB (28%)</div></td></tr><tr><td class="lh-table-column--thumbnail"><img class="lh-thumbnail" src="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&amp;token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c" alt="" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&amp;token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c"></td><td class="lh-table-column--url"><div class="lh-text__url" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&amp;token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c"><div class="lh-text">…o/2018-05-06T06%3A46%3A01.738Z.png?alt=…</div><div class="lh-text lh-text__url-host">(firebasestorage.googleapis.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">154&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">43&nbsp;KB (28%)</div></td></tr><tr><td class="lh-table-column--thumbnail"><img class="lh-thumbnail" src="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&amp;token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0" alt="" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&amp;token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0"></td><td class="lh-table-column--url"><div class="lh-text__url" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&amp;token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0"><div class="lh-text">…o/2018-05-06T06%3A44%3A20.265Z.png?alt=…</div><div class="lh-text lh-text__url-host">(firebasestorage.googleapis.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">151&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">42&nbsp;KB (28%)</div></td></tr><tr><td class="lh-table-column--thumbnail"><img class="lh-thumbnail" src="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A42%3A19.478Z.png?alt=media&amp;token=99f7a653-5780-411b-91c6-ca1a86b4a8a5" alt="" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A42%3A19.478Z.png?alt=media&amp;token=99f7a653-5780-411b-91c6-ca1a86b4a8a5"></td><td class="lh-table-column--url"><div class="lh-text__url" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A42%3A19.478Z.png?alt=media&amp;token=99f7a653-5780-411b-91c6-ca1a86b4a8a5"><div class="lh-text">…o/2018-05-06T06%3A42%3A19.478Z.png?alt=…</div><div class="lh-text lh-text__url-host">(firebasestorage.googleapis.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">142&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">39&nbsp;KB (28%)</div></td></tr><tr><td class="lh-table-column--thumbnail"><img class="lh-thumbnail" src="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A41%3A06.899Z.png?alt=media&amp;token=ab32239e-a34f-4a94-880a-bc03dec7121b" alt="" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A41%3A06.899Z.png?alt=media&amp;token=ab32239e-a34f-4a94-880a-bc03dec7121b"></td><td class="lh-table-column--url"><div class="lh-text__url" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A41%3A06.899Z.png?alt=media&amp;token=ab32239e-a34f-4a94-880a-bc03dec7121b"><div class="lh-text">…o/2018-05-06T06%3A41%3A06.899Z.png?alt=…</div><div class="lh-text lh-text__url-host">(firebasestorage.googleapis.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">136&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">38&nbsp;KB (28%)</div></td></tr><tr><td class="lh-table-column--thumbnail"><img class="lh-thumbnail" src="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&amp;token=60c2ac2a-de60-4ebc-b970-70264d96a80b" alt="" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&amp;token=60c2ac2a-de60-4ebc-b970-70264d96a80b"></td><td class="lh-table-column--url"><div class="lh-text__url" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&amp;token=60c2ac2a-de60-4ebc-b970-70264d96a80b"><div class="lh-text">…o/2018-05-06T06%3A45%3A15.468Z.png?alt=…</div><div class="lh-text lh-text__url-host">(firebasestorage.googleapis.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">133&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">37&nbsp;KB (28%)</div></td></tr><tr><td class="lh-table-column--thumbnail"><img class="lh-thumbnail" src="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&amp;token=d0181e98-3ea9-499b-865e-8cec92fa1e33" alt="" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&amp;token=d0181e98-3ea9-499b-865e-8cec92fa1e33"></td><td class="lh-table-column--url"><div class="lh-text__url" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&amp;token=d0181e98-3ea9-499b-865e-8cec92fa1e33"><div class="lh-text">…o/2018-05-06T06%3A43%3A05.377Z.png?alt=…</div><div class="lh-text lh-text__url-host">(firebasestorage.googleapis.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">106&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">30&nbsp;KB (28%)</div></td></tr></tbody></table></details></details><details class="lh-perf-hint lh-perf-hint--fail lh-expandable-details"><summary class="lh-perf-hint__summary lh-expandable-details__summary"><div class="lh-perf-hint__title">Serve images in next-gen formats</div><div class="lh-toggle-arrow" title="See resources"></div><div class="lh-perf-hint__sparkline" title="Potential savings of 463&nbsp;KB (~2,720&nbsp;ms)"><div class="lh-sparkline"><div class="lh-sparkline__bar" style="width: 68%;"></div></div></div><div class="lh-perf-hint__stats" title="Potential savings of 463&nbsp;KB (~2,720&nbsp;ms)"><div class="lh-perf-hint__primary-stat">2,720&nbsp;ms</div><div class="lh-perf-hint__secondary-stat">463 KB</div></div></summary><div class="lh-perf-hint__description"><span>Image formats like JPEG 2000, JPEG XR, and WebP often provide better compression than PNG or JPEG, which means faster downloads and less data consumption. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/webp">Learn more</a>.</span></div><details class="lh-details" open=""><summary>View Details</summary><table class="lh-table"><thead><tr><th class="lh-table-column--thumbnail"><div class="lh-text"></div></th><th class="lh-table-column--url"><div class="lh-text">URL</div></th><th class="lh-table-column--text"><div class="lh-text">Original</div></th><th class="lh-table-column--text"><div class="lh-text">Potential Savings</div></th></tr></thead><tbody><tr><td class="lh-table-column--thumbnail"><img class="lh-thumbnail" src="https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png" alt="" title="https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png"></td><td class="lh-table-column--url"><div class="lh-text__url" title="https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png"><div class="lh-text">…images/pwa.png</div><div class="lh-text lh-text__url-host">(facebookfeed-neel.firebaseapp.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">285&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">228&nbsp;KB (80%)</div></td></tr><tr><td class="lh-table-column--thumbnail"><img class="lh-thumbnail" src="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A32%3A53.884Z.png?alt=media&amp;token=aca0478e-23b6-45d9-90d7-594641c37b77" alt="" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A32%3A53.884Z.png?alt=media&amp;token=aca0478e-23b6-45d9-90d7-594641c37b77"></td><td class="lh-table-column--url"><div class="lh-text__url" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A32%3A53.884Z.png?alt=media&amp;token=aca0478e-23b6-45d9-90d7-594641c37b77"><div class="lh-text">…o/2018-05-06T06%3A32%3A53.884Z.png?alt=…</div><div class="lh-text lh-text__url-host">(firebasestorage.googleapis.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">210&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">44&nbsp;KB (21%)</div></td></tr><tr><td class="lh-table-column--thumbnail"><img class="lh-thumbnail" src="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A42%3A19.478Z.png?alt=media&amp;token=99f7a653-5780-411b-91c6-ca1a86b4a8a5" alt="" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A42%3A19.478Z.png?alt=media&amp;token=99f7a653-5780-411b-91c6-ca1a86b4a8a5"></td><td class="lh-table-column--url"><div class="lh-text__url" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A42%3A19.478Z.png?alt=media&amp;token=99f7a653-5780-411b-91c6-ca1a86b4a8a5"><div class="lh-text">…o/2018-05-06T06%3A42%3A19.478Z.png?alt=…</div><div class="lh-text lh-text__url-host">(firebasestorage.googleapis.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">142&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">32&nbsp;KB (23%)</div></td></tr><tr><td class="lh-table-column--thumbnail"><img class="lh-thumbnail" src="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&amp;token=60c2ac2a-de60-4ebc-b970-70264d96a80b" alt="" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&amp;token=60c2ac2a-de60-4ebc-b970-70264d96a80b"></td><td class="lh-table-column--url"><div class="lh-text__url" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&amp;token=60c2ac2a-de60-4ebc-b970-70264d96a80b"><div class="lh-text">…o/2018-05-06T06%3A45%3A15.468Z.png?alt=…</div><div class="lh-text lh-text__url-host">(firebasestorage.googleapis.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">133&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">32&nbsp;KB (24%)</div></td></tr><tr><td class="lh-table-column--thumbnail"><img class="lh-thumbnail" src="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&amp;token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0" alt="" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&amp;token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0"></td><td class="lh-table-column--url"><div class="lh-text__url" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&amp;token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0"><div class="lh-text">…o/2018-05-06T06%3A44%3A20.265Z.png?alt=…</div><div class="lh-text lh-text__url-host">(firebasestorage.googleapis.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">151&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">32&nbsp;KB (21%)</div></td></tr><tr><td class="lh-table-column--thumbnail"><img class="lh-thumbnail" src="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&amp;token=d0181e98-3ea9-499b-865e-8cec92fa1e33" alt="" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&amp;token=d0181e98-3ea9-499b-865e-8cec92fa1e33"></td><td class="lh-table-column--url"><div class="lh-text__url" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&amp;token=d0181e98-3ea9-499b-865e-8cec92fa1e33"><div class="lh-text">…o/2018-05-06T06%3A43%3A05.377Z.png?alt=…</div><div class="lh-text lh-text__url-host">(firebasestorage.googleapis.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">106&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">32&nbsp;KB (30%)</div></td></tr><tr><td class="lh-table-column--thumbnail"><img class="lh-thumbnail" src="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A41%3A06.899Z.png?alt=media&amp;token=ab32239e-a34f-4a94-880a-bc03dec7121b" alt="" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A41%3A06.899Z.png?alt=media&amp;token=ab32239e-a34f-4a94-880a-bc03dec7121b"></td><td class="lh-table-column--url"><div class="lh-text__url" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A41%3A06.899Z.png?alt=media&amp;token=ab32239e-a34f-4a94-880a-bc03dec7121b"><div class="lh-text">…o/2018-05-06T06%3A41%3A06.899Z.png?alt=…</div><div class="lh-text lh-text__url-host">(firebasestorage.googleapis.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">136&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">31&nbsp;KB (23%)</div></td></tr><tr><td class="lh-table-column--thumbnail"><img class="lh-thumbnail" src="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&amp;token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c" alt="" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&amp;token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c"></td><td class="lh-table-column--url"><div class="lh-text__url" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&amp;token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c"><div class="lh-text">…o/2018-05-06T06%3A46%3A01.738Z.png?alt=…</div><div class="lh-text lh-text__url-host">(firebasestorage.googleapis.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">154&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">31&nbsp;KB (20%)</div></td></tr></tbody></table></details></details><details class="lh-perf-hint lh-perf-hint--fail lh-expandable-details"><summary class="lh-perf-hint__summary lh-expandable-details__summary"><div class="lh-perf-hint__title">Reduce render-blocking stylesheets</div><div class="lh-toggle-arrow" title="See resources"></div><div class="lh-perf-hint__sparkline" title="5 resources delayed first paint by 854&nbsp;ms"><div class="lh-sparkline"><div class="lh-sparkline__bar" style="width: 21.35%;"></div></div></div><div class="lh-perf-hint__stats" title="5 resources delayed first paint by 854&nbsp;ms"><div class="lh-perf-hint__primary-stat">850&nbsp;ms</div></div></summary><div class="lh-perf-hint__description"><span>External stylesheets are blocking the first paint of your page. Consider delivering critical CSS via `&lt;style&gt;` tags and deferring non-critical styles. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/blocking-resources">Learn more</a>.</span></div><details class="lh-details" open=""><summary>View Details</summary><table class="lh-table"><thead><tr><th class="lh-table-column--url"><div class="lh-text">URL</div></th><th class="lh-table-column--text"><div class="lh-text">Size (KB)</div></th><th class="lh-table-column--text"><div class="lh-text">Delayed Paint By (ms)</div></th></tr></thead><tbody><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://fonts.googleapis.com/css?family=Roboto:400,700"><div class="lh-text">/css?family=Roboto:400,700</div><div class="lh-text lh-text__url-host">(fonts.googleapis.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">0.67&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">832&nbsp;ms</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://fonts.googleapis.com/icon?family=Material+Icons"><div class="lh-text">/icon?family=Material+Icons</div><div class="lh-text lh-text__url-host">(fonts.googleapis.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">0.36&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">837&nbsp;ms</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css"><div class="lh-text">…1.3.0/material.indigo-pink.min.css</div><div class="lh-text lh-text__url-host">(cdnjs.cloudflare.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">18.44&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">842&nbsp;ms</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://facebookfeed-neel.firebaseapp.com/src/css/app.css"><div class="lh-text">…css/app.css</div><div class="lh-text lh-text__url-host">(facebookfeed-neel.firebaseapp.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">0.2&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">850&nbsp;ms</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://facebookfeed-neel.firebaseapp.com/src/css/feed.css"><div class="lh-text">…css/feed.css</div><div class="lh-text lh-text__url-host">(facebookfeed-neel.firebaseapp.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">0.62&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">854&nbsp;ms</div></td></tr></tbody></table></details></details><details class="lh-perf-hint lh-perf-hint--pass lh-expandable-details"><summary class="lh-perf-hint__summary lh-expandable-details__summary"><div class="lh-perf-hint__title">Unused CSS rules</div><div class="lh-toggle-arrow" title="See resources"></div><div class="lh-perf-hint__sparkline" title="Potential savings of 17&nbsp;KB (~100&nbsp;ms)"><div class="lh-sparkline"><div class="lh-sparkline__bar" style="width: 2.5%;"></div></div></div><div class="lh-perf-hint__stats" title="Potential savings of 17&nbsp;KB (~100&nbsp;ms)"><div class="lh-perf-hint__primary-stat">100&nbsp;ms</div><div class="lh-perf-hint__secondary-stat">17 KB</div></div></summary><div class="lh-perf-hint__description"><span>Remove unused rules from stylesheets to reduce unnecessary bytes consumed by network activity. <a rel="noopener" target="_blank" href="https://developers.google.com/speed/docs/insights/OptimizeCSSDelivery">Learn more</a></span></div><details class="lh-details" open=""><summary>View Details</summary><table class="lh-table"><thead><tr><th class="lh-table-column--url"><div class="lh-text">URL</div></th><th class="lh-table-column--text"><div class="lh-text">Original</div></th><th class="lh-table-column--text"><div class="lh-text">Potential Savings</div></th></tr></thead><tbody><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css"><div class="lh-text">…1.3.0/material.indigo-pink.min.css</div><div class="lh-text lh-text__url-host">(cdnjs.cloudflare.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">18&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">17&nbsp;KB (92%)</div></td></tr></tbody></table></details></details><details class="lh-perf-hint lh-perf-hint--pass lh-expandable-details"><summary class="lh-perf-hint__summary lh-expandable-details__summary"><div class="lh-perf-hint__title">Enable text compression</div><div class="lh-toggle-arrow" title="See resources"></div><div class="lh-perf-hint__sparkline" title="Potential savings of 1&nbsp;KB (~10&nbsp;ms)"><div class="lh-sparkline"><div class="lh-sparkline__bar" style="width: 0.25%;"></div></div></div><div class="lh-perf-hint__stats" title="Potential savings of 1&nbsp;KB (~10&nbsp;ms)"><div class="lh-perf-hint__primary-stat">10&nbsp;ms</div><div class="lh-perf-hint__secondary-stat">1 KB</div></div></summary><div class="lh-perf-hint__description"><span>Text-based responses should be served with compression (gzip, deflate or brotli) to minimize total network bytes. <a rel="noopener" target="_blank" href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/optimize-encoding-and-transfer">Learn more</a>.</span></div><details class="lh-details" open=""><summary>View Details</summary><table class="lh-table"><thead><tr><th class="lh-table-column--url"><div class="lh-text">Uncompressed resource URL</div></th><th class="lh-table-column--text"><div class="lh-text">Original</div></th><th class="lh-table-column--text"><div class="lh-text">GZIP Savings</div></th></tr></thead><tbody><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://facebookfeed-neel.firebaseio.com/posts.json"><div class="lh-text">/posts.json</div><div class="lh-text lh-text__url-host">(facebookfeed-neel.firebaseio.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">2&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">1&nbsp;KB (66%)</div></td></tr></tbody></table></details></details></div><div class="lh-audit-group"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">Diagnostics</div><div class="lh-toggle-arrow   lh-toggle-arrow-unexpandable" title="See audits"></div></summary><div class="lh-audit-group__description"><span>More information about the performance of your application.</span></div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--numeric">77</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Uses inefficient cache policy on static assets:  12 assets found</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>A long cache lifetime can speed up repeat visits to your page. <a rel="noopener" target="_blank" href="https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching#cache-control">Learn more</a>.</span></div>
    <details class="lh-details" open=""><summary>View Details</summary><table class="lh-table"><thead><tr><th class="lh-table-column--url"><div class="lh-text">URL</div></th><th class="lh-table-column--text"><div class="lh-text">Cache TTL</div></th><th class="lh-table-column--text"><div class="lh-text">Size (KB)</div></th></tr></thead><tbody><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png"><div class="lh-text">…images/pwa.png</div><div class="lh-text lh-text__url-host">(facebookfeed-neel.firebaseapp.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">1&nbsp;h</div></td><td class="lh-table-column--text"><div class="lh-text">285&nbsp;KB</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://facebookfeed-neel.firebaseapp.com/src/js/material.min.js"><div class="lh-text">…js/material.min.js</div><div class="lh-text lh-text__url-host">(facebookfeed-neel.firebaseapp.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">1&nbsp;h</div></td><td class="lh-table-column--text"><div class="lh-text">12&nbsp;KB</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://facebookfeed-neel.firebaseapp.com/src/js/fetch.js"><div class="lh-text">…js/fetch.js</div><div class="lh-text lh-text__url-host">(facebookfeed-neel.firebaseapp.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">1&nbsp;h</div></td><td class="lh-table-column--text"><div class="lh-text">3&nbsp;KB</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://facebookfeed-neel.firebaseapp.com/src/js/feed.js"><div class="lh-text">…js/feed.js</div><div class="lh-text lh-text__url-host">(facebookfeed-neel.firebaseapp.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">1&nbsp;h</div></td><td class="lh-table-column--text"><div class="lh-text">3&nbsp;KB</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://facebookfeed-neel.firebaseapp.com/src/js/promise.js"><div class="lh-text">…js/promise.js</div><div class="lh-text lh-text__url-host">(facebookfeed-neel.firebaseapp.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">1&nbsp;h</div></td><td class="lh-table-column--text"><div class="lh-text">2&nbsp;KB</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://facebookfeed-neel.firebaseapp.com/src/js/idb.js"><div class="lh-text">…js/idb.js</div><div class="lh-text lh-text__url-host">(facebookfeed-neel.firebaseapp.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">1&nbsp;h</div></td><td class="lh-table-column--text"><div class="lh-text">2&nbsp;KB</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://facebookfeed-neel.firebaseapp.com/src/js/app.js"><div class="lh-text">…js/app.js</div><div class="lh-text lh-text__url-host">(facebookfeed-neel.firebaseapp.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">1&nbsp;h</div></td><td class="lh-table-column--text"><div class="lh-text">1&nbsp;KB</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://facebookfeed-neel.firebaseapp.com/src/js/utility.js"><div class="lh-text">…js/utility.js</div><div class="lh-text lh-text__url-host">(facebookfeed-neel.firebaseapp.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">1&nbsp;h</div></td><td class="lh-table-column--text"><div class="lh-text">1&nbsp;KB</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://facebookfeed-neel.firebaseapp.com/src/css/feed.css"><div class="lh-text">…css/feed.css</div><div class="lh-text lh-text__url-host">(facebookfeed-neel.firebaseapp.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">1&nbsp;h</div></td><td class="lh-table-column--text"><div class="lh-text">1&nbsp;KB</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://facebookfeed-neel.firebaseapp.com/src/css/app.css"><div class="lh-text">…css/app.css</div><div class="lh-text lh-text__url-host">(facebookfeed-neel.firebaseapp.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">1&nbsp;h</div></td><td class="lh-table-column--text"><div class="lh-text">0&nbsp;KB</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://fonts.googleapis.com/css?family=Roboto:400,700"><div class="lh-text">/css?family=Roboto:400,700</div><div class="lh-text lh-text__url-host">(fonts.googleapis.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">1&nbsp;d</div></td><td class="lh-table-column--text"><div class="lh-text">1&nbsp;KB</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://fonts.googleapis.com/icon?family=Material+Icons"><div class="lh-text">/icon?family=Material+Icons</div><div class="lh-text lh-text__url-host">(fonts.googleapis.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">1&nbsp;d</div></td><td class="lh-table-column--text"><div class="lh-text">0&nbsp;KB</div></td></tr></tbody></table></details></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative">
    <div class="lh-score__value lh-score__value--fail lh-score__value--binary">0</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Critical Request Chains:  15</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>The Critical Request Chains below show you what resources are issued with a high priority. Consider reducing the length of chains, reducing the download size of resources, or deferring the download of unnecessary resources to improve page load. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/critical-request-chains">Learn more</a>.</span></div>
    
  <style>
    .lh-crc .tree-marker {
      width: 12px;
      height: 26px;
      display: block;
      float: left;
      background-position: top left;
    }
    .lh-crc .horiz-down {
      background: url('data:image/svg+xml;utf8,<svg width="16" height="26" viewBox="0 0 16 26" xmlns="http://www.w3.org/2000/svg"><g fill="%23D8D8D8" fill-rule="evenodd"><path d="M16 12v2H-2v-2z"/><path d="M9 12v14H7V12z"/></g></svg>');
    }
    .lh-crc .right {
      background: url('data:image/svg+xml;utf8,<svg width="16" height="26" viewBox="0 0 16 26" xmlns="http://www.w3.org/2000/svg"><path d="M16 12v2H0v-2z" fill="%23D8D8D8" fill-rule="evenodd"/></svg>');
    }
    .lh-crc .up-right {
      background: url('data:image/svg+xml;utf8,<svg width="16" height="26" viewBox="0 0 16 26" xmlns="http://www.w3.org/2000/svg"><path d="M7 0h2v14H7zm2 12h7v2H9z" fill="%23D8D8D8" fill-rule="evenodd"/></svg>');
    }
    .lh-crc .vert-right {
      background: url('data:image/svg+xml;utf8,<svg width="16" height="26" viewBox="0 0 16 26" xmlns="http://www.w3.org/2000/svg"><path d="M7 0h2v27H7zm2 12h7v2H9z" fill="%23D8D8D8" fill-rule="evenodd"/></svg>');
    }
    .lh-crc .vert {
      background: url('data:image/svg+xml;utf8,<svg width="16" height="26" viewBox="0 0 16 26" xmlns="http://www.w3.org/2000/svg"><path d="M7 0h2v26H7z" fill="%23D8D8D8" fill-rule="evenodd"/></svg>');
    }
    .lh-crc .crc-tree {
      font-size: 14px;
      width: 100%;
      overflow-x: auto;
    }
    .lh-crc .crc-node {
      height: 26px;
      line-height: 26px;
      white-space: nowrap;
    }
    .lh-crc .crc-node__tree-value {
      margin-left: 10px;
    }
    .lh-crc .crc-node__chain-duration {
      font-weight: 700;
    }
    .lh-crc .crc-node__tree-hostname {
      color: #595959;
    }
    .lh-crc .crc-initial-nav {
      color: #595959;
      font-style: italic;
    }
  </style>
  <div class="lh-score__description">
    Longest chain: <b class="lh-crc__longest_duration">4,290.9ms</b>
    over <b class="lh-crc__longest_length">2</b> requests, totalling
    <b class="lh-crc__longest_transfersize">3.3&nbsp;KB</b>
  </div>
  <div class="lh-crc">
    <details class="lh-details" open="">
      <summary>View critical network waterfall:</summary>
      <div class="crc-initial-nav">Initial Navigation</div>
      <!-- stamp for each chain -->
      <template id="tmpl-lh-crc__chains">
        <div class="crc-node">
          <span class="crc-node__tree-marker">
            <!-- fill me -->
          </span>
          <span class="crc-node__tree-value">
            <span class="crc-node__tree-file"><!-- fill me: node.request.url.file --></span>
            <span class="crc-node__tree-hostname">(<!-- fill me: node.request.url.host -->)</span>
            <!-- fill me -->
          </span>
        </div>
      </template>
    
        <div class="crc-node" title="https://facebookfeed-neel.firebaseapp.com/">
          <span class="crc-node__tree-marker">
            <!-- fill me -->
          <span class="tree-marker up-right"></span><span class="tree-marker right"></span><span class="tree-marker horiz-down"></span></span>
          <span class="crc-node__tree-value">
            <span class="crc-node__tree-file">/</span>
            <span class="crc-node__tree-hostname">(facebookfeed-neel.firebaseapp.com)</span>
            <!-- fill me -->
          </span>
        </div>
      
        <div class="crc-node" title="https://fonts.googleapis.com/css?family=Roboto:400,700">
          <span class="crc-node__tree-marker">
            <!-- fill me -->
          <span class="tree-marker"></span><span class="tree-marker"></span><span class="tree-marker vert-right"></span><span class="tree-marker right"></span><span class="tree-marker right"></span></span>
          <span class="crc-node__tree-value">
            <span class="crc-node__tree-file">/css?family=Roboto:400,700</span>
            <span class="crc-node__tree-hostname">(fonts.googleapis.com)</span>
            <!-- fill me -->
          <span class="crc-node__chain-duration"> - 831.9ms, </span><span class="crc-node__chain-duration">0.67&nbsp;KB</span></span>
        </div>
      
        <div class="crc-node" title="https://fonts.googleapis.com/icon?family=Material+Icons">
          <span class="crc-node__tree-marker">
            <!-- fill me -->
          <span class="tree-marker"></span><span class="tree-marker"></span><span class="tree-marker vert-right"></span><span class="tree-marker right"></span><span class="tree-marker right"></span></span>
          <span class="crc-node__tree-value">
            <span class="crc-node__tree-file">/icon?family=Material+Icons</span>
            <span class="crc-node__tree-hostname">(fonts.googleapis.com)</span>
            <!-- fill me -->
          <span class="crc-node__chain-duration"> - 835.9ms, </span><span class="crc-node__chain-duration">0.36&nbsp;KB</span></span>
        </div>
      
        <div class="crc-node" title="https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css">
          <span class="crc-node__tree-marker">
            <!-- fill me -->
          <span class="tree-marker"></span><span class="tree-marker"></span><span class="tree-marker vert-right"></span><span class="tree-marker right"></span><span class="tree-marker right"></span></span>
          <span class="crc-node__tree-value">
            <span class="crc-node__tree-file">…1.3.0/material.indigo-pink.min.css</span>
            <span class="crc-node__tree-hostname">(cdnjs.cloudflare.com)</span>
            <!-- fill me -->
          <span class="crc-node__chain-duration"> - 839.6ms, </span><span class="crc-node__chain-duration">18.44&nbsp;KB</span></span>
        </div>
      
        <div class="crc-node" title="https://facebookfeed-neel.firebaseapp.com/src/css/app.css">
          <span class="crc-node__tree-marker">
            <!-- fill me -->
          <span class="tree-marker"></span><span class="tree-marker"></span><span class="tree-marker vert-right"></span><span class="tree-marker right"></span><span class="tree-marker right"></span></span>
          <span class="crc-node__tree-value">
            <span class="crc-node__tree-file">…css/app.css</span>
            <span class="crc-node__tree-hostname">(facebookfeed-neel.firebaseapp.com)</span>
            <!-- fill me -->
          <span class="crc-node__chain-duration"> - 839.4ms, </span><span class="crc-node__chain-duration">0.2&nbsp;KB</span></span>
        </div>
      
        <div class="crc-node" title="https://facebookfeed-neel.firebaseapp.com/src/css/feed.css">
          <span class="crc-node__tree-marker">
            <!-- fill me -->
          <span class="tree-marker"></span><span class="tree-marker"></span><span class="tree-marker vert-right"></span><span class="tree-marker right"></span><span class="tree-marker right"></span></span>
          <span class="crc-node__tree-value">
            <span class="crc-node__tree-file">…css/feed.css</span>
            <span class="crc-node__tree-hostname">(facebookfeed-neel.firebaseapp.com)</span>
            <!-- fill me -->
          <span class="crc-node__chain-duration"> - 842.5ms, </span><span class="crc-node__chain-duration">0.62&nbsp;KB</span></span>
        </div>
      
        <div class="crc-node" title="https://facebookfeed-neel.firebaseapp.com/src/js/promise.js">
          <span class="crc-node__tree-marker">
            <!-- fill me -->
          <span class="tree-marker"></span><span class="tree-marker"></span><span class="tree-marker vert-right"></span><span class="tree-marker right"></span><span class="tree-marker right"></span></span>
          <span class="crc-node__tree-value">
            <span class="crc-node__tree-file">…js/promise.js</span>
            <span class="crc-node__tree-hostname">(facebookfeed-neel.firebaseapp.com)</span>
            <!-- fill me -->
          <span class="crc-node__chain-duration"> - 587.6ms, </span><span class="crc-node__chain-duration">2.39&nbsp;KB</span></span>
        </div>
      
        <div class="crc-node" title="https://facebookfeed-neel.firebaseapp.com/src/js/fetch.js">
          <span class="crc-node__tree-marker">
            <!-- fill me -->
          <span class="tree-marker"></span><span class="tree-marker"></span><span class="tree-marker vert-right"></span><span class="tree-marker right"></span><span class="tree-marker right"></span></span>
          <span class="crc-node__tree-value">
            <span class="crc-node__tree-file">…js/fetch.js</span>
            <span class="crc-node__tree-hostname">(facebookfeed-neel.firebaseapp.com)</span>
            <!-- fill me -->
          <span class="crc-node__chain-duration"> - 634.6ms, </span><span class="crc-node__chain-duration">3.35&nbsp;KB</span></span>
        </div>
      
        <div class="crc-node" title="https://facebookfeed-neel.firebaseapp.com/src/js/idb.js">
          <span class="crc-node__tree-marker">
            <!-- fill me -->
          <span class="tree-marker"></span><span class="tree-marker"></span><span class="tree-marker vert-right"></span><span class="tree-marker right"></span><span class="tree-marker right"></span></span>
          <span class="crc-node__tree-value">
            <span class="crc-node__tree-file">…js/idb.js</span>
            <span class="crc-node__tree-hostname">(facebookfeed-neel.firebaseapp.com)</span>
            <!-- fill me -->
          <span class="crc-node__chain-duration"> - 626.3ms, </span><span class="crc-node__chain-duration">1.81&nbsp;KB</span></span>
        </div>
      
        <div class="crc-node" title="https://facebookfeed-neel.firebaseapp.com/src/js/utility.js">
          <span class="crc-node__tree-marker">
            <!-- fill me -->
          <span class="tree-marker"></span><span class="tree-marker"></span><span class="tree-marker vert-right"></span><span class="tree-marker right"></span><span class="tree-marker right"></span></span>
          <span class="crc-node__tree-value">
            <span class="crc-node__tree-file">…js/utility.js</span>
            <span class="crc-node__tree-hostname">(facebookfeed-neel.firebaseapp.com)</span>
            <!-- fill me -->
          <span class="crc-node__chain-duration"> - 594.7ms, </span><span class="crc-node__chain-duration">0.77&nbsp;KB</span></span>
        </div>
      
        <div class="crc-node" title="https://facebookfeed-neel.firebaseapp.com/src/js/app.js">
          <span class="crc-node__tree-marker">
            <!-- fill me -->
          <span class="tree-marker"></span><span class="tree-marker"></span><span class="tree-marker vert-right"></span><span class="tree-marker right"></span><span class="tree-marker right"></span></span>
          <span class="crc-node__tree-value">
            <span class="crc-node__tree-file">…js/app.js</span>
            <span class="crc-node__tree-hostname">(facebookfeed-neel.firebaseapp.com)</span>
            <!-- fill me -->
          <span class="crc-node__chain-duration"> - 621.5ms, </span><span class="crc-node__chain-duration">1.29&nbsp;KB</span></span>
        </div>
      
        <div class="crc-node" title="https://facebookfeed-neel.firebaseapp.com/src/js/feed.js">
          <span class="crc-node__tree-marker">
            <!-- fill me -->
          <span class="tree-marker"></span><span class="tree-marker"></span><span class="tree-marker vert-right"></span><span class="tree-marker right"></span><span class="tree-marker right"></span></span>
          <span class="crc-node__tree-value">
            <span class="crc-node__tree-file">…js/feed.js</span>
            <span class="crc-node__tree-hostname">(facebookfeed-neel.firebaseapp.com)</span>
            <!-- fill me -->
          <span class="crc-node__chain-duration"> - 642ms, </span><span class="crc-node__chain-duration">2.86&nbsp;KB</span></span>
        </div>
      
        <div class="crc-node" title="https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu4mxKKTU1Kg.woff2">
          <span class="crc-node__tree-marker">
            <!-- fill me -->
          <span class="tree-marker"></span><span class="tree-marker"></span><span class="tree-marker vert-right"></span><span class="tree-marker right"></span><span class="tree-marker right"></span></span>
          <span class="crc-node__tree-value">
            <span class="crc-node__tree-file">…v18/KFOmCnqEu….woff2</span>
            <span class="crc-node__tree-hostname">(fonts.gstatic.com)</span>
            <!-- fill me -->
          <span class="crc-node__chain-duration"> - 781.9ms, </span><span class="crc-node__chain-duration">10.56&nbsp;KB</span></span>
        </div>
      
        <div class="crc-node" title="https://fonts.gstatic.com/s/materialicons/v36/flUhRq6tzZclQEJ-Vdg-IuiaDsNcIhQ8tQ.woff2">
          <span class="crc-node__tree-marker">
            <!-- fill me -->
          <span class="tree-marker"></span><span class="tree-marker"></span><span class="tree-marker vert-right"></span><span class="tree-marker right"></span><span class="tree-marker right"></span></span>
          <span class="crc-node__tree-value">
            <span class="crc-node__tree-file">…v36/flUhRq6tz….woff2</span>
            <span class="crc-node__tree-hostname">(fonts.gstatic.com)</span>
            <!-- fill me -->
          <span class="crc-node__chain-duration"> - 1,260.8ms, </span><span class="crc-node__chain-duration">48.02&nbsp;KB</span></span>
        </div>
      
        <div class="crc-node" title="https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu7GxKKTU1Kvnz.woff2">
          <span class="crc-node__tree-marker">
            <!-- fill me -->
          <span class="tree-marker"></span><span class="tree-marker"></span><span class="tree-marker vert-right"></span><span class="tree-marker right"></span><span class="tree-marker right"></span></span>
          <span class="crc-node__tree-value">
            <span class="crc-node__tree-file">…v18/KFOmCnqEu….woff2</span>
            <span class="crc-node__tree-hostname">(fonts.gstatic.com)</span>
            <!-- fill me -->
          <span class="crc-node__chain-duration"> - 700.7ms, </span><span class="crc-node__chain-duration">7.93&nbsp;KB</span></span>
        </div>
      
        <div class="crc-node" title="https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu7WxKKTU1Kvnz.woff2">
          <span class="crc-node__tree-marker">
            <!-- fill me -->
          <span class="tree-marker"></span><span class="tree-marker"></span><span class="tree-marker up-right"></span><span class="tree-marker right"></span><span class="tree-marker right"></span></span>
          <span class="crc-node__tree-value">
            <span class="crc-node__tree-file">…v18/KFOmCnqEu….woff2</span>
            <span class="crc-node__tree-hostname">(fonts.gstatic.com)</span>
            <!-- fill me -->
          <span class="crc-node__chain-duration"> - 658.9ms, </span><span class="crc-node__chain-duration">3.3&nbsp;KB</span></span>
        </div>
      </details>
  </div>
</details>
  </div>
</div></div><details class="lh-audit-group lh-passed-audits"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">13 Passed Audits</div><div class="lh-toggle-arrow  " title="See audits"></div></summary><div class="lh-audit">
  <div class="lh-score lh-score--informative">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Reduce render-blocking scripts</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Script elements are blocking the first paint of your page. Consider inlining critical scripts and deferring non-critical ones. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/blocking-resources">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Minify CSS</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Minifying CSS files can reduce network payload sizes. <a rel="noopener" target="_blank" href="https://developers.google.com/speed/docs/insights/MinifyResources">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Minify JavaScript</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Minifying JavaScript files can reduce payload sizes and script parse time. <a rel="noopener" target="_blank" href="https://developers.google.com/speed/docs/insights/MinifyResources">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Optimize images</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Optimized images load faster and consume less cellular data. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/optimize-images">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Keep server response times low (TTFB):  560&nbsp;ms</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Time To First Byte identifies the time at which your server sends a response. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/chrome-devtools/network-performance/issues">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Avoids page redirects:  0&nbsp;ms</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Redirects introduce additional delays before the page can be loaded. <a rel="noopener" target="_blank" href="https://developers.google.com/speed/docs/insights/AvoidRedirects">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative">
    <div class="lh-score__value lh-score__value--pass lh-score__value--numeric">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Preload key requests:  0&nbsp;ms</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Consider using &lt;link rel=preload&gt; to prioritize fetching late-discovered resources sooner <a rel="noopener" target="_blank" href="https://developers.google.com/web/updates/2016/03/link-rel-preload">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--numeric">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Avoids enormous network payloads:  Total size was 404&nbsp;KB</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Large network payloads cost users real money and are highly correlated with long load times. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/network-payloads">Learn more</a>.</span></div>
    <details class="lh-details" open=""><summary>View Details</summary><table class="lh-table"><thead><tr><th class="lh-table-column--url"><div class="lh-text">URL</div></th><th class="lh-table-column--text"><div class="lh-text">Total Size</div></th><th class="lh-table-column--text"><div class="lh-text">Transfer Time</div></th></tr></thead><tbody><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png"><div class="lh-text">…images/pwa.png</div><div class="lh-text lh-text__url-host">(facebookfeed-neel.firebaseapp.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">285&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">1,670&nbsp;ms</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://fonts.gstatic.com/s/materialicons/v36/flUhRq6tzZclQEJ-Vdg-IuiaDsNcIhQ8tQ.woff2"><div class="lh-text">…v36/flUhRq6tz….woff2</div><div class="lh-text lh-text__url-host">(fonts.gstatic.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">48&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">280&nbsp;ms</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css"><div class="lh-text">…1.3.0/material.indigo-pink.min.css</div><div class="lh-text lh-text__url-host">(cdnjs.cloudflare.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">18&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">110&nbsp;ms</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://facebookfeed-neel.firebaseapp.com/src/js/material.min.js"><div class="lh-text">…js/material.min.js</div><div class="lh-text lh-text__url-host">(facebookfeed-neel.firebaseapp.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">12&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">70&nbsp;ms</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu4mxKKTU1Kg.woff2"><div class="lh-text">…v18/KFOmCnqEu….woff2</div><div class="lh-text lh-text__url-host">(fonts.gstatic.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">11&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">60&nbsp;ms</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu7GxKKTU1Kvnz.woff2"><div class="lh-text">…v18/KFOmCnqEu….woff2</div><div class="lh-text lh-text__url-host">(fonts.gstatic.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">8&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">50&nbsp;ms</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://facebookfeed-neel.firebaseapp.com/src/js/fetch.js"><div class="lh-text">…js/fetch.js</div><div class="lh-text lh-text__url-host">(facebookfeed-neel.firebaseapp.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">3&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">20&nbsp;ms</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu7WxKKTU1Kvnz.woff2"><div class="lh-text">…v18/KFOmCnqEu….woff2</div><div class="lh-text lh-text__url-host">(fonts.gstatic.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">3&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">20&nbsp;ms</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://facebookfeed-neel.firebaseapp.com/src/js/feed.js"><div class="lh-text">…js/feed.js</div><div class="lh-text lh-text__url-host">(facebookfeed-neel.firebaseapp.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">3&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">20&nbsp;ms</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://facebookfeed-neel.firebaseio.com/posts.json"><div class="lh-text">/posts.json</div><div class="lh-text lh-text__url-host">(facebookfeed-neel.firebaseio.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">2&nbsp;KB</div></td><td class="lh-table-column--text"><div class="lh-text">10&nbsp;ms</div></td></tr></tbody></table></details></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--numeric">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Avoids an excessive DOM size:  207 nodes</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Browser engineers recommend pages contain fewer than ~1,500 DOM nodes. The sweet spot is a tree depth &lt; 32 elements and fewer than 60 children/parent element. A large DOM can increase memory usage, cause longer <a rel="noopener" target="_blank" href="https://developers.google.com/web/fundamentals/performance/rendering/reduce-the-scope-and-complexity-of-style-calculations">style calculations</a>, and produce costly <a rel="noopener" target="_blank" href="https://developers.google.com/speed/articles/reflow">layout reflows</a>. <a rel="noopener" target="_blank" href="https://developers.google.com/web/fundamentals/performance/rendering/">Learn more</a>.</span></div>
    <details class="lh-details" open=""><summary>View details</summary><div class="lh-scorecards"><div class="lh-scorecard"><div class="lh-scorecard__title">Total DOM Nodes</div><div class="lh-scorecard__value">207</div><div class="lh-scorecard__target">target: &lt; 1,500 nodes</div></div><div class="lh-scorecard" title="html.mdl-js >
  body >
    div#app >
      div.mdl-layout__container >
        div.mdl-layout.mdl-js-layout.mdl-layout--fixed-header.has-drawer.is-small-screen.is-upgraded >
          main.mdl-layout__content.mat-typography >
            div#create-post >
              form >
                div.input-section >
                  div#location-loader.mdl-spinner.mdl-js-spinner.is-active.is-upgraded >
                    div.mdl-spinner__layer.mdl-spinner__layer-1 >
                      div.mdl-spinner__circle-clipper.mdl-spinner__left >
                        div.mdl-spinner__circle"><div class="lh-scorecard__title">DOM Depth</div><div class="lh-scorecard__value">13</div><div class="lh-scorecard__target">target: &lt; 32</div></div><div class="lh-scorecard" title="Element with most children:
head"><div class="lh-scorecard__title">Maximum Children</div><div class="lh-scorecard__value">25</div><div class="lh-scorecard__target">target: &lt; 60 nodes</div></div></div></details></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>User Timing marks and measures:  0</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Consider instrumenting your app with the User Timing API to create custom, real-world measurements of key user experiences. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/user-timing">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>JavaScript boot-up time:  750&nbsp;ms</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Consider reducing the time spent parsing, compiling, and executing JS. You may find delivering smaller JS payloads helps with this. <a rel="noopener" target="_blank" href="https://developers.google.com/web/lighthouse/audits/bootup">Learn more</a>.</span></div>
    <details class="lh-details" open=""><summary>View Details</summary><table class="lh-table"><thead><tr><th class="lh-table-column--url"><div class="lh-text">URL</div></th><th class="lh-table-column--text"><div class="lh-text">Script Evaluation</div></th><th class="lh-table-column--text"><div class="lh-text">Script Parsing &amp; Compile</div></th></tr></thead><tbody><tr><td class="lh-table-column--url"><div class="lh-text__url" title="chrome-extension://aapbdbdomjkkjkaonfhkkikfgjllcleb/bubble_compiled.js"><div class="lh-text">/bubble_compiled.js</div><div class="lh-text lh-text__url-host">(aapbdbdomjkkjkaonfhkkikfgjllcleb)</div></div></td><td class="lh-table-column--text"><div class="lh-text">103&nbsp;ms</div></td><td class="lh-table-column--text"><div class="lh-text">89&nbsp;ms</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/ext/common.js"><div class="lh-text">/ext/common.js</div><div class="lh-text lh-text__url-host">(gighmmpiobklfepjocnamgkkbiglidom)</div></div></td><td class="lh-table-column--text"><div class="lh-text">118&nbsp;ms</div></td><td class="lh-table-column--text"><div class="lh-text">1&nbsp;ms</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/include.preload.js"><div class="lh-text">/include.preload.js</div><div class="lh-text lh-text__url-host">(gighmmpiobklfepjocnamgkkbiglidom)</div></div></td><td class="lh-table-column--text"><div class="lh-text">40&nbsp;ms</div></td><td class="lh-table-column--text"><div class="lh-text">11&nbsp;ms</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/content.js"><div class="lh-text">/js/content.js</div><div class="lh-text lh-text__url-host">(cmkdbmfndkfgebldhnkbfhlneefdaaip)</div></div></td><td class="lh-table-column--text"><div class="lh-text">47&nbsp;ms</div></td><td class="lh-table-column--text"><div class="lh-text">1&nbsp;ms</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="chrome-extension://fmkadmapgofadopljbjfkapdkoienihi/build/inject.js"><div class="lh-text">/build/inject.js</div><div class="lh-text lh-text__url-host">(fmkadmapgofadopljbjfkapdkoienihi)</div></div></td><td class="lh-table-column--text"><div class="lh-text">8&nbsp;ms</div></td><td class="lh-table-column--text"><div class="lh-text">8&nbsp;ms</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/notification.js"><div class="lh-text">/js/notification.js</div><div class="lh-text lh-text__url-host">(cmkdbmfndkfgebldhnkbfhlneefdaaip)</div></div></td><td class="lh-table-column--text"><div class="lh-text">7&nbsp;ms</div></td><td class="lh-table-column--text"><div class="lh-text">8&nbsp;ms</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/adblock-bandaids.js"><div class="lh-text">/adblock-bandaids.js</div><div class="lh-text lh-text__url-host">(gighmmpiobklfepjocnamgkkbiglidom)</div></div></td><td class="lh-table-column--text"><div class="lh-text">9&nbsp;ms</div></td><td class="lh-table-column--text"><div class="lh-text">4&nbsp;ms</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/wrs_env.js"><div class="lh-text">/js/wrs_env.js</div><div class="lh-text lh-text__url-host">(cmkdbmfndkfgebldhnkbfhlneefdaaip)</div></div></td><td class="lh-table-column--text"><div class="lh-text">12&nbsp;ms</div></td><td class="lh-table-column--text"><div class="lh-text">2&nbsp;ms</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/browser-polyfill.js"><div class="lh-text">/js/browser-polyfill.js</div><div class="lh-text lh-text__url-host">(cmkdbmfndkfgebldhnkbfhlneefdaaip)</div></div></td><td class="lh-table-column--text"><div class="lh-text">7&nbsp;ms</div></td><td class="lh-table-column--text"><div class="lh-text">6&nbsp;ms</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://facebookfeed-neel.firebaseapp.com/src/js/feed.js"><div class="lh-text">…js/feed.js</div><div class="lh-text lh-text__url-host">(facebookfeed-neel.firebaseapp.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">6&nbsp;ms</div></td><td class="lh-table-column--text"><div class="lh-text">6&nbsp;ms</div></td></tr></tbody></table></details></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Main thread work breakdown:  1,600&nbsp;ms</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Consider reducing the time spent parsing, compiling and executing JS.You may find delivering smaller JS payloads helps with this.</span></div>
    <details class="lh-details" open=""><summary>View Details</summary><table class="lh-table"><thead><tr><th class="lh-table-column--text"><div class="lh-text">Category</div></th><th class="lh-table-column--text"><div class="lh-text">Work</div></th><th class="lh-table-column--text"><div class="lh-text">Time spent</div></th></tr></thead><tbody><tr><td class="lh-table-column--text"><div class="lh-text">Script Evaluation</div></td><td class="lh-table-column--text"><div class="lh-text">Evaluate Script</div></td><td class="lh-table-column--text"><div class="lh-text">449&nbsp;ms</div></td></tr><tr><td class="lh-table-column--text"><div class="lh-text">Script Evaluation</div></td><td class="lh-table-column--text"><div class="lh-text">Run Microtasks</div></td><td class="lh-table-column--text"><div class="lh-text">79&nbsp;ms</div></td></tr><tr><td class="lh-table-column--text"><div class="lh-text">Style &amp; Layout</div></td><td class="lh-table-column--text"><div class="lh-text">Recalculate Style</div></td><td class="lh-table-column--text"><div class="lh-text">288&nbsp;ms</div></td></tr><tr><td class="lh-table-column--text"><div class="lh-text">Style &amp; Layout</div></td><td class="lh-table-column--text"><div class="lh-text">Layout</div></td><td class="lh-table-column--text"><div class="lh-text">153&nbsp;ms</div></td></tr><tr><td class="lh-table-column--text"><div class="lh-text">Garbage collection</div></td><td class="lh-table-column--text"><div class="lh-text">DOM GC</div></td><td class="lh-table-column--text"><div class="lh-text">85&nbsp;ms</div></td></tr><tr><td class="lh-table-column--text"><div class="lh-text">Garbage collection</div></td><td class="lh-table-column--text"><div class="lh-text">Minor GC</div></td><td class="lh-table-column--text"><div class="lh-text">67&nbsp;ms</div></td></tr><tr><td class="lh-table-column--text"><div class="lh-text">Garbage collection</div></td><td class="lh-table-column--text"><div class="lh-text">Major GC</div></td><td class="lh-table-column--text"><div class="lh-text">37&nbsp;ms</div></td></tr><tr><td class="lh-table-column--text"><div class="lh-text">Script Parsing &amp; Compile</div></td><td class="lh-table-column--text"><div class="lh-text">Compile Script</div></td><td class="lh-table-column--text"><div class="lh-text">184&nbsp;ms</div></td></tr><tr><td class="lh-table-column--text"><div class="lh-text">Parsing HTML &amp; CSS</div></td><td class="lh-table-column--text"><div class="lh-text">Parse HTML</div></td><td class="lh-table-column--text"><div class="lh-text">107&nbsp;ms</div></td></tr><tr><td class="lh-table-column--text"><div class="lh-text">Parsing HTML &amp; CSS</div></td><td class="lh-table-column--text"><div class="lh-text">Parse Stylesheet</div></td><td class="lh-table-column--text"><div class="lh-text">38&nbsp;ms</div></td></tr><tr><td class="lh-table-column--text"><div class="lh-text">Compositing</div></td><td class="lh-table-column--text"><div class="lh-text">Update Layer Tree</div></td><td class="lh-table-column--text"><div class="lh-text">56&nbsp;ms</div></td></tr><tr><td class="lh-table-column--text"><div class="lh-text">Compositing</div></td><td class="lh-table-column--text"><div class="lh-text">Composite Layers</div></td><td class="lh-table-column--text"><div class="lh-text">13&nbsp;ms</div></td></tr><tr><td class="lh-table-column--text"><div class="lh-text">Paint</div></td><td class="lh-table-column--text"><div class="lh-text">Paint</div></td><td class="lh-table-column--text"><div class="lh-text">41&nbsp;ms</div></td></tr></tbody></table></details></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>All text remains visible during webfont loads</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Leverage the font-display CSS feature to ensure text is user-visible while webfonts are loading. <a rel="noopener" target="_blank" href="https://developers.google.com/web/updates/2016/02/font-display">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div></details></div><div class="lh-category"><span class="lh-permalink" id="pwa"></span>
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--numeric">100</div>
    <div class="lh-score__gauge">
  
  <a href="#pwa" class="lh-gauge__wrapper">
    <div class="lh-gauge lh-gauge--pass" data-progress="100">
      <div class="lh-gauge__circle">
        <div class="lh-gauge__mask lh-gauge__mask--full" style="transform: rotate(180deg);">
          <div class="lh-gauge__fill" style="transform: rotate(180deg);"></div>
        </div>
        <div class="lh-gauge__mask lh-gauge__mask--half">
          <div class="lh-gauge__fill" style="transform: rotate(180deg);"></div>
          <div class="lh-gauge__fill lh-gauge__fill--fix" style="transform: rotate(360deg);"></div>
        </div>
      </div>
      <div class="lh-gauge__percentage">100</div>
    </div>
    <div class="lh-gauge__label">Progressive Web App</div>
  </a>
</div>
    <div class="lh-score__header">
      <div class="lh-score__snippet">
        <span class="lh-score__title"><!-- fill me --><span>Progressive Web App</span></span>
      </div>
      <div class="lh-score__description"><!-- fill me --><span>These checks validate the aspects of a Progressive Web App, as specified by the baseline <a rel="noopener" target="_blank" href="https://developers.google.com/web/progressive-web-apps/checklist">PWA Checklist</a>.</span></div>
    </div>
  </div>
<div class="lh-audit-group lh-failed-audits"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">1 Failed Audits</div><div class="lh-toggle-arrow   lh-toggle-arrow-unexpandable" title="See audits"></div></summary><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Page load is fast enough on 3G</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>A fast page load over a 3G network ensures a good mobile user experience. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/fast-3g">Learn more</a>.</span></div>
    <details class="lh-details" open=""><summary>View Details</summary><table class="lh-table"><thead><tr><th class="lh-table-column--url"><div class="lh-text">URL</div></th><th class="lh-table-column--text"><div class="lh-text">Latency (ms)</div></th></tr></thead><tbody><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://facebookfeed-neel.firebaseapp.com/"><div class="lh-text">/</div><div class="lh-text lh-text__url-host">(facebookfeed-neel.firebaseapp.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">564.35</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://fonts.googleapis.com/css?family=Roboto:400,700"><div class="lh-text">/css?family=Roboto:400,700</div><div class="lh-text lh-text__url-host">(fonts.googleapis.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">571.17</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css"><div class="lh-text">…1.3.0/material.indigo-pink.min.css</div><div class="lh-text lh-text__url-host">(cdnjs.cloudflare.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">583.66</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu4mxKKTU1Kg.woff2"><div class="lh-text">…v18/KFOmCnqEu….woff2</div><div class="lh-text lh-text__url-host">(fonts.gstatic.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">630.16</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://facebookfeed-neel.firebaseio.com/posts.json"><div class="lh-text">/posts.json</div><div class="lh-text lh-text__url-host">(facebookfeed-neel.firebaseio.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">585.11</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&amp;token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c"><div class="lh-text">…o/2018-05-06T06%3A46%3A01.738Z.png?alt=…</div><div class="lh-text lh-text__url-host">(firebasestorage.googleapis.com)</div></div></td><td class="lh-table-column--text"><div class="lh-text">0.2</div></td></tr><tr><td class="lh-table-column--url"><div class="lh-text__url" title="chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/wrs_env.js"><div class="lh-text">/js/wrs_env.js</div><div class="lh-text lh-text__url-host">(cmkdbmfndkfgebldhnkbfhlneefdaaip)</div></div></td><td class="lh-table-column--text"><div class="lh-text">0.04</div></td></tr></tbody></table></details></details>
  </div>
<div class="lh-debug">First Interactive was found at 4,500&nbsp;ms; however, the network request latencies were not sufficiently realistic, so the performance measurements cannot be trusted.</div></div></div><details class="lh-audit-group lh-passed-audits"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">10 Passed Audits</div><div class="lh-toggle-arrow  " title="See audits"></div></summary><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Registers a service worker</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>The service worker is the technology that enables your app to use many Progressive Web App features, such as offline, add to homescreen, and push notifications. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/registered-service-worker">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Responds with a 200 when offline</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>If you're building a Progressive Web App, consider using a service worker so that your app can work offline. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/http-200-when-offline">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Contains some content when JavaScript is not available</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Your app should display some content when JavaScript is disabled, even if it's just a warning to the user that JavaScript is required to use the app. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/no-js">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Uses HTTPS</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>All sites should be protected with HTTPS, even ones that don't handle sensitive data. HTTPS prevents intruders from tampering with or passively listening in on the communications between your app and your users, and is a prerequisite for HTTP/2 and many new web platform APIs. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/https">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Redirects HTTP traffic to HTTPS</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>If you've already set up HTTPS, make sure that you redirect all HTTP traffic to HTTPS. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/http-redirects-to-https">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>User can be prompted to Install the Web App</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Browsers can proactively prompt users to add your app to their homescreen, which can lead to higher engagement. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/install-prompt">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Configured for a custom splash screen</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>A themed splash screen ensures a high-quality experience when users launch your app from their homescreens. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/custom-splash-screen">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Address bar matches brand colors</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>The browser address bar can be themed to match your site. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/address-bar">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Has a <code>&lt;meta name="viewport"&gt;</code> tag with <code>width</code> or <code>initial-scale</code></span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Add a viewport meta tag to optimize your app for mobile screens. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/has-viewport-meta-tag">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Content is sized correctly for the viewport</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>If the width of your app's content doesn't match the width of the viewport, your app might not be optimized for mobile screens. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/content-sized-correctly-for-viewport">Learn more</a>.</span></div>
    </details>
  </div>
</div></details><details class="lh-audit-group lh-audit-group--manual"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">Additional items to manually check</div><div class="lh-toggle-arrow  " title="See audits"></div></summary><div class="lh-audit-group__description"><span>These checks are required by the baseline <a rel="noopener" target="_blank" href="https://developers.google.com/web/progressive-web-apps/checklist">PWA Checklist</a> but are not automatically checked by Lighthouse. They do not affect your score but it's important that you verify them manually.</span></div><div class="lh-audit">
  <div class="lh-score lh-score--informative lh-score--manual">
    <div class="lh-score__value lh-score__value--fail lh-score__value--binary">0</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Site works cross-browser</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>To reach the most number of users, sites should work across every major browser. <a rel="noopener" target="_blank" href="https://developers.google.com/web/progressive-web-apps/checklist#site-works-cross-browser">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative lh-score--manual">
    <div class="lh-score__value lh-score__value--fail lh-score__value--binary">0</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Page transitions don't feel like they block on the network</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Transitions should feel snappy as you tap around, even on a slow network, a key to perceived performance. <a rel="noopener" target="_blank" href="https://developers.google.com/web/progressive-web-apps/checklist#page-transitions-dont-feel-like-they-block-on-the-network">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative lh-score--manual">
    <div class="lh-score__value lh-score__value--fail lh-score__value--binary">0</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Each page has a URL</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Ensure individual pages are deep linkable via the URLs and that URLs are unique for the purpose of shareability on social media. <a rel="noopener" target="_blank" href="https://developers.google.com/web/progressive-web-apps/checklist#each-page-has-a-url">Learn more</a>.</span></div>
    </details>
  </div>
</div></details></div><div class="lh-category"><span class="lh-permalink" id="accessibility"></span>
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--numeric">97</div>
    <div class="lh-score__gauge">
  
  <a href="#accessibility" class="lh-gauge__wrapper">
    <div class="lh-gauge lh-gauge--pass" data-progress="97">
      <div class="lh-gauge__circle">
        <div class="lh-gauge__mask lh-gauge__mask--full" style="transform: rotate(174deg);">
          <div class="lh-gauge__fill" style="transform: rotate(174deg);"></div>
        </div>
        <div class="lh-gauge__mask lh-gauge__mask--half">
          <div class="lh-gauge__fill" style="transform: rotate(174deg);"></div>
          <div class="lh-gauge__fill lh-gauge__fill--fix" style="transform: rotate(348deg);"></div>
        </div>
      </div>
      <div class="lh-gauge__percentage">97</div>
    </div>
    <div class="lh-gauge__label">Accessibility</div>
  </a>
</div>
    <div class="lh-score__header">
      <div class="lh-score__snippet">
        <span class="lh-score__title"><!-- fill me --><span>Accessibility</span></span>
      </div>
      <div class="lh-score__description"><!-- fill me --><span>These checks highlight opportunities to <a rel="noopener" target="_blank" href="https://developers.google.com/web/fundamentals/accessibility">improve the accessibility of your web app</a>. Only a subset of accessibility issues can be automatically detected so manual testing is also encouraged.</span></div>
    </div>
  </div>
<div class="lh-audit-group"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">Meta Tags Used Properly</div><div class="lh-toggle-arrow   lh-toggle-arrow-unexpandable" title="See audits"></div></summary><div class="lh-audit-group__description"><span>These are opportunities to improve the user experience of your site.</span></div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--fail lh-score__value--binary">0</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span><code>[user-scalable="no"]</code> is used in the <code>&lt;meta name="viewport"&gt;</code> element or the <code>[maximum-scale]</code> attribute is less than 5.</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Disabling zooming is problematic for users with low vision who rely on screen magnification to properly see the contents of a web page. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/meta-viewport?application=lighthouse">Learn more</a>.</span></div>
    <details class="lh-details" open=""><summary class="lh-list__header">View failing elements</summary><div class="lh-list__items"><span class="lh-list__item"><span class="lh-node" title="meta[name=&quot;viewport&quot;]" data-path="1,HTML,0,HEAD,1,META" data-selector="meta[name=&quot;viewport&quot;]" data-snippet="<meta name=&quot;viewport&quot; content=&quot;width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0&quot;>">&lt;meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0"&gt;</span></span></div></details></details>
  </div>
</div></div><details class="lh-audit-group lh-passed-audits"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">19 Passed Audits</div><div class="lh-toggle-arrow  " title="See audits"></div></summary><details class="lh-audit-group"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">Elements Use Attributes Correctly</div><div class="lh-toggle-arrow  " title="See audits"></div></summary><div class="lh-audit-group__description"><span>These are opportunities to improve the configuration of your HTML elements.</span></div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Image elements have <code>[alt]</code> attributes</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Informative elements should aim for short, descriptive alternate text. Decorative elements can be ignored with an empty alt attribute.<a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/image-alt?application=lighthouse">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>No element has a <code>[tabindex]</code> value greater than 0</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>A value greater than 0 implies an explicit navigation ordering. Although technically valid, this often creates frustrating experiences for users who rely on assistive technologies. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/tabindex?application=lighthouse">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div></details><details class="lh-audit-group"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">ARIA Attributes Follow Best Practices</div><div class="lh-toggle-arrow  " title="See audits"></div></summary><div class="lh-audit-group__description"><span>These are opportunities to improve the usage of ARIA in your application which may enhance the experience for users of assistive technology, like a screen reader.</span></div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span><code>[aria-*]</code> attributes match their roles</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Each ARIA `role` supports a specific subset of `aria-*` attributes. Mismatching these invalidates the `aria-*` attributes. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/aria-allowed-attr?application=lighthouse">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span><code>[role]</code>s have all required <code>[aria-*]</code> attributes</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Some ARIA roles have required attributes that describe the state of the element to screen readers. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/aria-required-attr?application=lighthouse">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Elements with <code>[role]</code> that require specific children <code>[role]</code>s, are present</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Some ARIA parent roles must contain specific child roles to perform their intended accessibility functions. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/aria-required-children?application=lighthouse">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span><code>[role]</code>s are contained by their required parent element</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Some ARIA child roles must be contained by specific parent roles to properly perform their intended accessibility functions. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/aria-required-parent?application=lighthouse">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span><code>[role]</code> values are valid</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>ARIA roles must have valid values in order to perform their intended accessibility functions. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/aria-roles?application=lighthouse">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span><code>[aria-*]</code> attributes have valid values</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Assistive technologies, like screen readers, can't interpret ARIA attributes with invalid values. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/aria-valid-attr-value?application=lighthouse">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span><code>[aria-*]</code> attributes are valid and not misspelled</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Assistive technologies, like screen readers, can't interpret ARIA attributes with invalid names. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/aria-valid-attr?application=lighthouse">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div></details><details class="lh-audit-group"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">Elements Have Discernible Names</div><div class="lh-toggle-arrow  " title="See audits"></div></summary><div class="lh-audit-group__description"><span>These are opportunities to improve the semantics of the controls in your application. This may enhance the experience for users of assistive technology, like a screen reader.</span></div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Buttons have an accessible name</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>When a button doesn't have an accessible name, screen readers announce it as "button", making it unusable for users who rely on screen readers. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/button-name?application=lighthouse">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div></details><details class="lh-audit-group"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">Elements Describe Contents Well</div><div class="lh-toggle-arrow  " title="See audits"></div></summary><div class="lh-audit-group__description"><span>These are opportunities to make your content easier to understand for a user of assistive technology, like a screen reader.</span></div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>The page contains a heading, skip link, or landmark region</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Adding ways to bypass repetitive content lets keyboard users navigate the page more efficiently. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/bypass?application=lighthouse">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Document has a <code>&lt;title&gt;</code> element</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>The title gives screen reader users an overview of the page, and search engine users rely on it heavily to determine if a page is relevant to their search. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/title">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Form elements have associated labels</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Labels ensure that form controls are announced properly by assistive technologies, like screen readers. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/label?application=lighthouse">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span><code>&lt;video&gt;</code> elements contain a <code>&lt;track&gt;</code> element with <code>[kind="captions"]</code></span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>When a video provides a caption it is easier for deaf and hearing impaired users to access its information. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/video-caption?application=lighthouse">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span><code>&lt;video&gt;</code> elements contain a <code>&lt;track&gt;</code> element with <code>[kind="description"]</code></span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Audio descriptions provide relevant information for videos that dialogue cannot, such as facial expressions and scenes. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/video-description?application=lighthouse">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div></details><details class="lh-audit-group"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">Color Contrast Is Satisfactory</div><div class="lh-toggle-arrow  " title="See audits"></div></summary><div class="lh-audit-group__description"><span>These are opportunities to improve the legibility of your content.</span></div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Background and foreground colors have a sufficient contrast ratio</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Low-contrast text is difficult or impossible for many users to read. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/color-contrast?application=lighthouse">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div></details><details class="lh-audit-group"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">Elements Are Well Structured</div><div class="lh-toggle-arrow  " title="See audits"></div></summary><div class="lh-audit-group__description"><span>These are opportunities to make sure your HTML is appropriately structured.</span></div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span><code>[id]</code> attributes on the page are unique</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>The value of an id attribute must be unique to prevent other instances from being overlooked by assistive technologies. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/duplicate-id?application=lighthouse">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div></details><details class="lh-audit-group"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">Page Specifies Valid Language</div><div class="lh-toggle-arrow  " title="See audits"></div></summary><div class="lh-audit-group__description"><span>These are opportunities to improve the interpretation of your content by users in different locales.</span></div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span><code>&lt;html&gt;</code> element has a <code>[lang]</code> attribute</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>If a page doesn't specify a lang attribute, a screen reader assumes that the page is in the default language that the user chose when setting up the screen reader. If the page isn't actually in the default language, then the screen reader might not announce the page's text correctly. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/html-lang?application=lighthouse">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span><code>&lt;html&gt;</code> element has a valid value for its <code>[lang]</code> attribute</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Specifying a valid <a rel="noopener" target="_blank" href="https://www.w3.org/International/questions/qa-choosing-language-tags#question">BCP 47 language</a> helps screen readers announce text properly. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/valid-lang?application=lighthouse">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div></details></details><details class="lh-audit-group lh-audit-group--notapplicable"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">15 Not Applicable Audits</div><div class="lh-toggle-arrow  " title="See audits"></div></summary><details class="lh-audit-group"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">Elements Use Attributes Correctly</div><div class="lh-toggle-arrow  " title="See audits"></div></summary><div class="lh-audit-group__description"><span>These are opportunities to improve the configuration of your HTML elements.</span></div><div class="lh-audit">
  <div class="lh-score lh-score--informative">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span><code>[accesskey]</code> values are not unique</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Access keys let users quickly focus a part of the page. For proper navigation, each access key must be unique. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/accesskeys?application=lighthouse">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span><code>&lt;audio&gt;</code> elements are missing a <code>&lt;track&gt;</code> element with <code>[kind="captions"]</code>.</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Captions make audio elements usable for deaf or hearing-impaired users, providing critical information such as who is talking, what they're saying, and other non-speech information. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/audio-caption?application=lighthouse">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span><code>&lt;input type="image"&gt;</code> elements do not have <code>[alt]</code> text</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>When an image is being used as an `&lt;input&gt;` button, providing alternative text can help screen reader users understand the purpose of the button. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/input-image-alt?application=lighthouse">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Cells in a <code>&lt;table&gt;</code> element that use the <code>[headers]</code> attribute refers to other cells of that same table.</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Screen readers have features to make navigating tables easier. Ensuring `&lt;td&gt;` cells using the `[headers]` attribute only refer to other cells in the same table may improve the experience for screen reader users. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/td-headers-attr?application=lighthouse">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span><code>&lt;th&gt;</code> elements and elements with <code>[role="columnheader"/"rowheader"]</code> do not have data cells they describe.</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Screen readers have features to make navigating tables easier. Ensuring table headers always refer to some set of cells may improve the experience for screen reader users. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/th-has-data-cells?application=lighthouse">Learn more</a>.</span></div>
    </details>
  </div>
</div></details><details class="lh-audit-group"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">Elements Have Discernible Names</div><div class="lh-toggle-arrow  " title="See audits"></div></summary><div class="lh-audit-group__description"><span>These are opportunities to improve the semantics of the controls in your application. This may enhance the experience for users of assistive technology, like a screen reader.</span></div><div class="lh-audit">
  <div class="lh-score lh-score--informative">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Links do not have a discernible name</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Link text (and alternate text for images, when used as links) that is discernible, unique, and focusable improves the navigation experience for screen reader users. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/link-name?application=lighthouse">Learn more</a>.</span></div>
    </details>
  </div>
</div></details><details class="lh-audit-group"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">Elements Describe Contents Well</div><div class="lh-toggle-arrow  " title="See audits"></div></summary><div class="lh-audit-group__description"><span>These are opportunities to make your content easier to understand for a user of assistive technology, like a screen reader.</span></div><div class="lh-audit">
  <div class="lh-score lh-score--informative">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span><code>&lt;frame&gt;</code> or <code>&lt;iframe&gt;</code> elements do not have a title</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Screen reader users rely on frame titles to describe the contents of frames. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/frame-title?application=lighthouse">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Presentational <code>&lt;table&gt;</code> elements do not avoid using <code>&lt;th&gt;</code>, <code>&lt;caption&gt;</code> or the <code>[summary]</code> attribute.</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>A table being used for layout purposes should not include data elements, such as the th or caption elements or the summary attribute, because this can create a confusing experience for screen reader users. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/layout-table?application=lighthouse">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span><code>&lt;object&gt;</code> elements do not have <code>[alt]</code> text</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Screen readers cannot translate non-text content. Adding alt text to `&lt;object&gt;` elements helps screen readers convey meaning to users. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/object-alt?application=lighthouse">Learn more</a>.</span></div>
    </details>
  </div>
</div></details><details class="lh-audit-group"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">Elements Are Well Structured</div><div class="lh-toggle-arrow  " title="See audits"></div></summary><div class="lh-audit-group__description"><span>These are opportunities to make sure your HTML is appropriately structured.</span></div><div class="lh-audit">
  <div class="lh-score lh-score--informative">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span><code>&lt;dl&gt;</code>'s do not contain only properly-ordered <code>&lt;dt&gt;</code> and <code>&lt;dd&gt;</code> groups, <code>&lt;script&gt;</code> or <code>&lt;template&gt;</code> elements.</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>When definition lists are not properly marked up, screen readers may produce confusing or inaccurate output. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/definition-list?application=lighthouse">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Definition list items are not wrapped in <code>&lt;dl&gt;</code> elements</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Definition list items (`&lt;dt&gt;` and `&lt;dd&gt;`) must be wrapped in a parent `&lt;dl&gt;` element to ensure that screen readers can properly announce them. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/dlitem?application=lighthouse">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Lists do not contain only <code>&lt;li&gt;</code> elements and script supporting elements (<code>&lt;script&gt;</code> and <code>&lt;template&gt;</code>).</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Screen readers have a specific way of announcing lists. Ensuring proper list structure aids screen reader output. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/list?application=lighthouse">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>List items (<code>&lt;li&gt;</code>) are not contained within <code>&lt;ul&gt;</code> or <code>&lt;ol&gt;</code> parent elements.</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Screen readers require list items (`&lt;li&gt;`) to be contained within a parent `&lt;ul&gt;` or `&lt;ol&gt;` to be announced properly. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/listitem?application=lighthouse">Learn more</a>.</span></div>
    </details>
  </div>
</div></details><details class="lh-audit-group"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">Page Specifies Valid Language</div><div class="lh-toggle-arrow  " title="See audits"></div></summary><div class="lh-audit-group__description"><span>These are opportunities to improve the interpretation of your content by users in different locales.</span></div><div class="lh-audit">
  <div class="lh-score lh-score--informative">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span><code>[lang]</code> attributes do not have a valid value</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Specifying a valid <a rel="noopener" target="_blank" href="https://www.w3.org/International/questions/qa-choosing-language-tags#question">BCP 47 language</a> on elements helps ensure that text is pronounced correctly by a screen reader. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/valid-lang?application=lighthouse">Learn more</a>.</span></div>
    </details>
  </div>
</div></details><details class="lh-audit-group"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">Meta Tags Used Properly</div><div class="lh-toggle-arrow  " title="See audits"></div></summary><div class="lh-audit-group__description"><span>These are opportunities to improve the user experience of your site.</span></div><div class="lh-audit">
  <div class="lh-score lh-score--informative">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>The document uses <code>&lt;meta http-equiv="refresh"&gt;</code></span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Users do not expect a page to refresh automatically, and doing so will move focus back to the top of the page. This may create a frustrating or confusing experience. <a rel="noopener" target="_blank" href="https://dequeuniversity.com/rules/axe/2.2/meta-refresh?application=lighthouse">Learn more</a>.</span></div>
    </details>
  </div>
</div></details></details><details class="lh-audit-group lh-audit-group--manual"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">Additional items to manually check</div><div class="lh-toggle-arrow  " title="See audits"></div></summary><div class="lh-audit-group__description"><span>These items address areas which an automated testing tool cannot cover. Learn more in our guide on <a rel="noopener" target="_blank" href="https://developers.google.com/web/fundamentals/accessibility/how-to-review">conducting an accessibility review</a>.</span></div><div class="lh-audit">
  <div class="lh-score lh-score--informative lh-score--manual">
    <div class="lh-score__value lh-score__value--fail lh-score__value--binary">0</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>The page has a logical tab order</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Tabbing through the page follows the visual layout. Users cannot focus elements that are offscreen. <a rel="noopener" target="_blank" href="https://developers.google.com/web/fundamentals/accessibility/how-to-review#start_with_the_keyboard">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative lh-score--manual">
    <div class="lh-score__value lh-score__value--fail lh-score__value--binary">0</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Interactive controls are keyboard focusable</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Custom interactive controls are keyboard focusable and display a focus indicator. <a rel="noopener" target="_blank" href="https://developers.google.com/web/fundamentals/accessibility/how-to-review#start_with_the_keyboard">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative lh-score--manual">
    <div class="lh-score__value lh-score__value--fail lh-score__value--binary">0</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>The user's focus is directed to new content added to the page</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>If new content, such as a dialog, is added to the page, the user's focus is directed to it. <a rel="noopener" target="_blank" href="https://developers.google.com/web/fundamentals/accessibility/how-to-review#start_with_the_keyboard">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative lh-score--manual">
    <div class="lh-score__value lh-score__value--fail lh-score__value--binary">0</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>User focus is not accidentally trapped in a region</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>A user can tab into and out of any control or region without accidentally trapping their focus. <a rel="noopener" target="_blank" href="https://developers.google.com/web/fundamentals/accessibility/how-to-review#start_with_the_keyboard">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative lh-score--manual">
    <div class="lh-score__value lh-score__value--fail lh-score__value--binary">0</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Custom controls have associated labels</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Custom interactive controls have associated labels, provided by aria-label or aria-labelledby. <a rel="noopener" target="_blank" href="https://developers.google.com/web/fundamentals/accessibility/how-to-review#try_it_with_a_screen_reader">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative lh-score--manual">
    <div class="lh-score__value lh-score__value--fail lh-score__value--binary">0</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Custom controls have ARIA roles</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Custom interactive controls have appropriate ARIA roles. <a rel="noopener" target="_blank" href="https://developers.google.com/web/fundamentals/accessibility/how-to-review#try_it_with_a_screen_reader">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative lh-score--manual">
    <div class="lh-score__value lh-score__value--fail lh-score__value--binary">0</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Visual order on the page follows DOM order</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>DOM order matches the visual order, improving navigation for assistive technology. <a rel="noopener" target="_blank" href="https://developers.google.com/web/fundamentals/accessibility/how-to-review#try_it_with_a_screen_reader">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative lh-score--manual">
    <div class="lh-score__value lh-score__value--fail lh-score__value--binary">0</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Offscreen content is hidden from assistive technology</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Offscreen content is hidden with display: none or aria-hidden=true. <a rel="noopener" target="_blank" href="https://developers.google.com/web/fundamentals/accessibility/how-to-review#try_it_with_a_screen_reader">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative lh-score--manual">
    <div class="lh-score__value lh-score__value--fail lh-score__value--binary">0</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Headings don't skip levels</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Headings are used to create an outline for the page and heading levels are not skipped. <a rel="noopener" target="_blank" href="https://developers.google.com/web/fundamentals/accessibility/how-to-review#take_advantage_of_headings_and_landmarks">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative lh-score--manual">
    <div class="lh-score__value lh-score__value--fail lh-score__value--binary">0</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>HTML5 landmark elements are used to improve navigation</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Landmark elements (&lt;main&gt;, &lt;nav&gt;, etc.) are used to improve the keyboard navigation of the page for assistive technology. <a rel="noopener" target="_blank" href="https://developers.google.com/web/fundamentals/accessibility/how-to-review#take_advantage_of_headings_and_landmarks">Learn more</a>.</span></div>
    </details>
  </div>
</div></details></div><div class="lh-category"><span class="lh-permalink" id="best-practices"></span>
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--numeric">100</div>
    <div class="lh-score__gauge">
  
  <a href="#best-practices" class="lh-gauge__wrapper">
    <div class="lh-gauge lh-gauge--pass" data-progress="100">
      <div class="lh-gauge__circle">
        <div class="lh-gauge__mask lh-gauge__mask--full" style="transform: rotate(180deg);">
          <div class="lh-gauge__fill" style="transform: rotate(180deg);"></div>
        </div>
        <div class="lh-gauge__mask lh-gauge__mask--half">
          <div class="lh-gauge__fill" style="transform: rotate(180deg);"></div>
          <div class="lh-gauge__fill lh-gauge__fill--fix" style="transform: rotate(360deg);"></div>
        </div>
      </div>
      <div class="lh-gauge__percentage">100</div>
    </div>
    <div class="lh-gauge__label">Best Practices</div>
  </a>
</div>
    <div class="lh-score__header">
      <div class="lh-score__snippet">
        <span class="lh-score__title"><!-- fill me --><span>Best Practices</span></span>
      </div>
      <div class="lh-score__description"><!-- fill me --><span>We've compiled some recommendations for modernizing your web app and avoiding performance pitfalls.</span></div>
    </div>
  </div>
<details class="lh-audit-group lh-passed-audits"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">16 Passed Audits</div><div class="lh-toggle-arrow  " title="See audits"></div></summary><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Avoids Application Cache</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Application Cache is deprecated. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/appcache">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Avoids WebSQL DB</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Web SQL is deprecated. Consider using IndexedDB instead. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/web-sql">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Uses HTTPS</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>All sites should be protected with HTTPS, even ones that don't handle sensitive data. HTTPS prevents intruders from tampering with or passively listening in on the communications between your app and your users, and is a prerequisite for HTTP/2 and many new web platform APIs. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/https">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Uses HTTP/2 for its own resources</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>HTTP/2 offers many benefits over HTTP/1.1, including binary headers, multiplexing, and server push. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/http2">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Uses passive listeners to improve scrolling performance</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Consider marking your touch and wheel event listeners as `passive` to improve your page's scroll performance. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/passive-event-listeners">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Avoids Mutation Events in its own scripts</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Mutation Events are deprecated and harm performance. Consider using Mutation Observers instead. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/mutation-events">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Avoids <code>document.write()</code></span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>For users on slow connections, external scripts dynamically injected via `document.write()` can delay page load by tens of seconds. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/document-write">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Opens external anchors using <code>rel="noopener"</code></span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Open new tabs using `rel="noopener"` to improve performance and prevent security vulnerabilities. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/noopener">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Avoids requesting the geolocation permission on page load</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Users are mistrustful of or confused by sites that request their location without context. Consider tying the request to user gestures instead. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/geolocation-on-load">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Avoids front-end JavaScript libraries with known security vulnerabilities</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Some third-party scripts may contain known security vulnerabilities  that are easily identified and exploited by attackers.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Avoids requesting the notification permission on page load</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Users are mistrustful of or confused by sites that request to send notifications without context. Consider tying the request to user gestures instead. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/notifications-on-load">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Avoids deprecated APIs</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Deprecated APIs will eventually be removed from the browser. <a rel="noopener" target="_blank" href="https://www.chromestatus.com/features#deprecated">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Manifest's <code>short_name</code> won't be truncated when displayed on homescreen</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Make your app's `short_name` fewer than 12 characters to ensure that it's not truncated on homescreens. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/manifest-short_name-is-not-truncated">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Allows users to paste into password fields</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Preventing password pasting undermines good security policy. <a rel="noopener" target="_blank" href="https://www.ncsc.gov.uk/blog-post/let-them-paste-passwords">Learn more</a></span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>No browser errors logged to the console</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Errors logged to the console indicate unresolved problems. They can come from network request failures and other browser concerns.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Displays images with correct aspect ratio</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Image display dimensions should match natural aspect ratio.</span></div>
    <span></span></details>
  </div>
</div></details></div><div class="lh-category"><span class="lh-permalink" id="seo"></span>
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--numeric">89</div>
    <div class="lh-score__gauge">
  
  <a href="#seo" class="lh-gauge__wrapper">
    <div class="lh-gauge lh-gauge--pass" data-progress="89">
      <div class="lh-gauge__circle">
        <div class="lh-gauge__mask lh-gauge__mask--full" style="transform: rotate(160deg);">
          <div class="lh-gauge__fill" style="transform: rotate(160deg);"></div>
        </div>
        <div class="lh-gauge__mask lh-gauge__mask--half">
          <div class="lh-gauge__fill" style="transform: rotate(160deg);"></div>
          <div class="lh-gauge__fill lh-gauge__fill--fix" style="transform: rotate(320deg);"></div>
        </div>
      </div>
      <div class="lh-gauge__percentage">89</div>
    </div>
    <div class="lh-gauge__label">SEO</div>
  </a>
</div>
    <div class="lh-score__header">
      <div class="lh-score__snippet">
        <span class="lh-score__title"><!-- fill me --><span>SEO</span></span>
      </div>
      <div class="lh-score__description"><!-- fill me --><span>These checks ensure that your page is optimized for search engine results ranking. There are additional factors Lighthouse does not check that may affect your search ranking. <a rel="noopener" target="_blank" href="https://support.google.com/webmasters/answer/35769">Learn more</a>.</span></div>
    </div>
  </div>
<div class="lh-audit-group"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">Content Best Practices</div><div class="lh-toggle-arrow   lh-toggle-arrow-unexpandable" title="See audits"></div></summary><div class="lh-audit-group__description"><span>Format your HTML in a way that enables crawlers to better understand your app’s content.</span></div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--fail lh-score__value--binary">0</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Document does not have a meta description</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Meta descriptions may be included in search results to concisely summarize page content. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/description">Learn more</a>.</span></div>
    </details>
  </div>
</div></div><details class="lh-audit-group lh-passed-audits"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">8 Passed Audits</div><div class="lh-toggle-arrow  " title="See audits"></div></summary><details class="lh-audit-group"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">Mobile Friendly</div><div class="lh-toggle-arrow  " title="See audits"></div></summary><div class="lh-audit-group__description"><span>Make sure your pages are mobile friendly so users don’t have to pinch or zoom in order to read the content pages. <a rel="noopener" target="_blank" href="https://developers.google.com/search/mobile-sites/">Learn more</a>.</span></div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Has a <code>&lt;meta name="viewport"&gt;</code> tag with <code>width</code> or <code>initial-scale</code></span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Add a viewport meta tag to optimize your app for mobile screens. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/has-viewport-meta-tag">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Document uses legible font sizes</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Font sizes less than 12px are too small to be legible and require mobile visitors to “pinch to zoom” in order to read. Strive to have &gt;60% of page text ≥12px. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/font-sizes">Learn more</a>.</span></div>
    <details class="lh-details" open=""><summary>View Details</summary><table class="lh-table"><thead><tr><th class="lh-table-column--url"><div class="lh-text">Source</div></th><th class="lh-table-column--code"><div class="lh-text">Selector</div></th><th class="lh-table-column--text"><div class="lh-text">% of Page Text</div></th><th class="lh-table-column--text"><div class="lh-text">Font Size</div></th></tr></thead><tbody><tr><td class="lh-table-column--url"><div class="lh-text__url"><div class="lh-text">Legible text</div></div></td><td class="lh-table-column--code"><pre class="lh-code"></pre></td><td class="lh-table-column--text"><div class="lh-text">100.00%</div></td><td class="lh-table-column--text"><div class="lh-text">≥ 12px</div></td></tr></tbody></table></details></details>
  </div>
</div></details><details class="lh-audit-group"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">Content Best Practices</div><div class="lh-toggle-arrow  " title="See audits"></div></summary><div class="lh-audit-group__description"><span>Format your HTML in a way that enables crawlers to better understand your app’s content.</span></div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Document has a <code>&lt;title&gt;</code> element</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>The title gives screen reader users an overview of the page, and search engine users rely on it heavily to determine if a page is relevant to their search. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/title">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Links have descriptive text</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Descriptive link text helps search engines understand your content. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/descriptive-link-text">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Document has a valid <code>hreflang</code></span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>hreflang allows crawlers to discover alternate translations of the page content. <a rel="noopener" target="_blank" href="https://support.google.com/webmasters/answer/189077">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Document avoids plugins</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Most mobile devices do not support plugins, and many desktop browsers restrict them.</span></div>
    <span></span></details>
  </div>
</div></details><details class="lh-audit-group"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">Crawling and Indexing</div><div class="lh-toggle-arrow  " title="See audits"></div></summary><div class="lh-audit-group__description"><span>To appear in search results, crawlers need access to your app.</span></div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Page has successful HTTP status code</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Pages with unsuccessful HTTP status codes may not be indexed properly. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/successful-http-code">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Page isn’t blocked from indexing</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Search engines are unable to include your pages in search results if they don't have permission to crawl them. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/indexing">Learn more</a>.</span></div>
    <span></span></details>
  </div>
</div></details></details><details class="lh-audit-group lh-audit-group--notapplicable"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">1 Not Applicable Audits</div><div class="lh-toggle-arrow  " title="See audits"></div></summary><details class="lh-audit-group"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">Content Best Practices</div><div class="lh-toggle-arrow  " title="See audits"></div></summary><div class="lh-audit-group__description"><span>Format your HTML in a way that enables crawlers to better understand your app’s content.</span></div><div class="lh-audit">
  <div class="lh-score lh-score--informative">
    <div class="lh-score__value lh-score__value--pass lh-score__value--binary">100</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Document has a valid <code>rel=canonical</code></span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Canonical links suggest which URL to show in search results. <a rel="noopener" target="_blank" href="https://developers.google.com/web/tools/lighthouse/audits/canonical">Learn more</a>.</span></div>
    </details>
  </div>
</div></details></details><details class="lh-audit-group lh-audit-group--manual"><summary class="lh-audit-group__summary"><div class="lh-audit-group__header">Additional items to manually check</div><div class="lh-toggle-arrow  " title="See audits"></div></summary><div class="lh-audit-group__description"><span>Run these additional validators on your site to check additional SEO best practices.</span></div><div class="lh-audit">
  <div class="lh-score lh-score--informative lh-score--manual">
    <div class="lh-score__value lh-score__value--fail lh-score__value--binary">0</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Page is mobile friendly</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Take the <a rel="noopener" target="_blank" href="https://search.google.com/test/mobile-friendly">Mobile-Friendly Test</a> to check for audits not covered by Lighthouse, like sizing tap targets appropriately. <a rel="noopener" target="_blank" href="https://developers.google.com/search/mobile-sites/">Learn more</a>.</span></div>
    </details>
  </div>
</div><div class="lh-audit">
  <div class="lh-score lh-score--informative lh-score--manual">
    <div class="lh-score__value lh-score__value--fail lh-score__value--binary">0</div>
    <details class="lh-score__header lh-expandable-details">
      <summary class="lh-score__snippet lh-expandable-details__summary">
        <span class="lh-score__title"><!-- fill me --><span>Structured data is valid</span></span>
        <div class="lh-toggle-arrow" title="See audits"></div>
      </summary>
      <div class="lh-score__description"><!-- fill me --><span>Run the <a rel="noopener" target="_blank" href="https://search.google.com/structured-data/testing-tool/">Structured Data Testing Tool</a> and the <a rel="noopener" target="_blank" href="http://linter.structured-data.org/">Structured Data Linter</a> to validate structured data. <a rel="noopener" target="_blank" href="https://developers.google.com/search/docs/guides/mark-up-content">Learn more</a>.</span></div>
    </details>
  </div>
</div></details></div></div>
  <style>
    .lh-footer {
      min-height: 90px;
      display: flex;
      align-items: center;
      justify-content: center;
      background-color: var(--report-header-bg-color);
      border-top: 1px solid var(--report-secondary-border-color);
    }

    .lh-footer span {
      text-align: center;
    }
  </style>
  <footer class="lh-footer">
    <span>
      Generated by <b>Lighthouse</b> <span class="lh-footer__version">2.9.3</span> on
      <span class="lh-footer__timestamp">May 6, 2018, 12:10 AM PDT</span> |
      <a href="https://github.com/GoogleChrome/Lighthouse/issues" target="_blank" rel="noopener">File an issue</a>
    </span>
  </footer>
</div></div></main>

  <div id="lh-log"></div>

  <script>/**
 * @license Copyright 2017 Google Inc. All Rights Reserved.
 * Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0
 * Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
 */
'use strict';

/* globals self URL */

const ELLIPSIS = '\u2026';
const NBSP = '\xa0';

const RATINGS = {
  PASS: {label: 'pass', minScore: 75},
  AVERAGE: {label: 'average', minScore: 45},
  FAIL: {label: 'fail'},
};

class Util {
  /**
   * Convert a score to a rating label.
   * @param {number} score
   * @return {string}
   */
  static calculateRating(score) {
    let rating = RATINGS.FAIL.label;
    if (score >= RATINGS.PASS.minScore) {
      rating = RATINGS.PASS.label;
    } else if (score >= RATINGS.AVERAGE.minScore) {
      rating = RATINGS.AVERAGE.label;
    }
    return rating;
  }

  /**
   * Format number.
   * @param {number} number
   * @param {number=} decimalPlaces Number of decimal places to include. Defaults to 1.
   * @return {string}
   */
  static formatNumber(number, decimalPlaces = 1) {
    return number.toLocaleString(undefined, {maximumFractionDigits: decimalPlaces});
  }

  /**
   * @param {number} size
   * @param {number=} decimalPlaces Number of decimal places to include. Defaults to 2.
   * @return {string}
   */
  static formatBytesToKB(size, decimalPlaces = 2) {
    const kbs = (size / 1024).toLocaleString(undefined, {maximumFractionDigits: decimalPlaces});
    return `${kbs}${NBSP}KB`;
  }

  /**
   * @param {number} ms
   * @param {number=} granularity Controls how coarse the displayed value is, defaults to 10
   * @return {string}
   */
  static formatMilliseconds(ms, granularity = 10) {
    const coarseTime = Math.round(ms / granularity) * granularity;
    return `${coarseTime.toLocaleString()}${NBSP}ms`;
  }

  /**
   * Format time.
   * @param {string} date
   * @return {string}
   */
  static formatDateTime(date) {
    const options = {
      month: 'short', day: 'numeric', year: 'numeric',
      hour: 'numeric', minute: 'numeric', timeZoneName: 'short',
    };
    let formatter = new Intl.DateTimeFormat('en-US', options);

    // Force UTC if runtime timezone could not be detected.
    // See https://github.com/GoogleChrome/lighthouse/issues/1056
    const tz = formatter.resolvedOptions().timeZone;
    if (!tz || tz.toLowerCase() === 'etc/unknown') {
      options.timeZone = 'UTC';
      formatter = new Intl.DateTimeFormat('en-US', options);
    }
    return formatter.format(new Date(date));
  }
  /**
   * Converts a time in seconds into a duration string, i.e. `1d 2h 13m 52s`
   * @param {number} timeInSeconds
   * @param {string=} zeroLabel
   * @return {string}
   */
  static formatDuration(timeInSeconds, zeroLabel = 'None') {
    if (timeInSeconds === 0) {
      return zeroLabel;
    }

    /** @type {!Array<string>} */
    const parts = [];
    const unitLabels = /** @type {!Object<string, number>} */ ({
      d: 60 * 60 * 24,
      h: 60 * 60,
      m: 60,
      s: 1,
    });

    Object.keys(unitLabels).forEach(label => {
      const unit = unitLabels[label];
      const numberOfUnits = Math.floor(timeInSeconds / unit);
      if (numberOfUnits > 0) {
        timeInSeconds -= numberOfUnits * unit;
        parts.push(`${numberOfUnits}\xa0${label}`);
      }
    });

    return parts.join(' ');
  }

  /**
   * @param {!URL} parsedUrl
   * @param {{numPathParts: (number|undefined), preserveQuery: (boolean|undefined), preserveHost: (boolean|undefined)}=} options
   * @return {string}
   */
  static getURLDisplayName(parsedUrl, options) {
    options = options || {};
    const numPathParts = options.numPathParts !== undefined ? options.numPathParts : 2;
    const preserveQuery = options.preserveQuery !== undefined ? options.preserveQuery : true;
    const preserveHost = options.preserveHost || false;

    let name;

    if (parsedUrl.protocol === 'about:' || parsedUrl.protocol === 'data:') {
      // Handle 'about:*' and 'data:*' URLs specially since they have no path.
      name = parsedUrl.href;
    } else {
      name = parsedUrl.pathname;
      const parts = name.split('/').filter(part => part.length);
      if (numPathParts && parts.length > numPathParts) {
        name = ELLIPSIS + parts.slice(-1 * numPathParts).join('/');
      }

      if (preserveHost) {
        name = `${parsedUrl.host}/${name.replace(/^\//, '')}`;
      }
      if (preserveQuery) {
        name = `${name}${parsedUrl.search}`;
      }
    }

    const MAX_LENGTH = 64;
    // Always elide hexadecimal hash
    name = name.replace(/([a-f0-9]{7})[a-f0-9]{13}[a-f0-9]*/g, `$1${ELLIPSIS}`);
    // Also elide other hash-like mixed-case strings
    name = name.replace(/([a-zA-Z0-9-_]{9})(?=.*[a-z])(?=.*[A-Z])(?=.*[0-9])[a-zA-Z0-9-_]{10,}/g,
        `$1${ELLIPSIS}`);
    // Also elide long number sequences
    name = name.replace(/(\d{3})\d{6,}/g, `$1${ELLIPSIS}`);
    // Merge any adjacent ellipses
    name = name.replace(/\u2026+/g, ELLIPSIS);

    // Elide query params first
    if (name.length > MAX_LENGTH && name.includes('?')) {
      // Try to leave the first query parameter intact
      name = name.replace(/\?([^=]*)(=)?.*/, `?$1$2${ELLIPSIS}`);

      // Remove it all if it's still too long
      if (name.length > MAX_LENGTH) {
        name = name.replace(/\?.*/, `?${ELLIPSIS}`);
      }
    }

    // Elide too long names next
    if (name.length > MAX_LENGTH) {
      const dotIndex = name.lastIndexOf('.');
      if (dotIndex >= 0) {
        name = name.slice(0, MAX_LENGTH - 1 - (name.length - dotIndex)) +
            // Show file extension
            `${ELLIPSIS}${name.slice(dotIndex)}`;
      } else {
        name = name.slice(0, MAX_LENGTH - 1) + ELLIPSIS;
      }
    }

    return name;
  }

  /**
   * Split a URL into a file and hostname for easy display.
   * @param {string} url
   * @return {{file: string, hostname: string}}
   */
  static parseURL(url) {
    const parsedUrl = new URL(url);
    return {file: Util.getURLDisplayName(parsedUrl), hostname: parsedUrl.hostname};
  }

  /**
   * @param {number} startTime
   * @param {number} endTime
   * @return {string}
   */
  static chainDuration(startTime, endTime) {
    return Util.formatNumber((endTime - startTime) * 1000);
  }
}

if (typeof module !== 'undefined' && module.exports) {
  module.exports = Util;
} else {
  // @ts-ignore
  self.Util = Util;
}
;
/**
 * @license Copyright 2017 Google Inc. All Rights Reserved.
 * Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0
 * Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
 */
'use strict';

/* globals URL self */

class DOM {
  /**
   * @param {!Document} document
   */
  constructor(document) {
    /** @private {!Document} */
    this._document = document;
  }

  /**
   * @param {string} name
   * @param {string=} className
   * @param {!Object<string, (string|undefined)>=} attrs Attribute key/val pairs.
   *     Note: if an attribute key has an undefined value, this method does not
   *     set the attribute on the node.
   * @return {!Element}
   */
  createElement(name, className, attrs = {}) {
    const element = this._document.createElement(name);
    if (className) {
      element.className = className;
    }
    Object.keys(attrs).forEach(key => {
      const value = attrs[key];
      if (typeof value !== 'undefined') {
        element.setAttribute(key, value);
      }
    });
    return element;
  }

  /**
   * @param {!Element} parentElem
   * @param {string} elementName
   * @param {string=} className
   * @param {!Object<string, (string|undefined)>=} attrs Attribute key/val pairs.
   *     Note: if an attribute key has an undefined value, this method does not
   *     set the attribute on the node.
   * @return {!Element}
   */
  createChildOf(parentElem, elementName, className, attrs) {
    const element = this.createElement(elementName, className, attrs);
    parentElem.appendChild(element);
    return element;
  }

  /**
   * @param {string} selector
   * @param {!Node} context
   * @return {!DocumentFragment} A clone of the template content.
   * @throws {Error}
   */
  cloneTemplate(selector, context) {
    const template = /** @type {?HTMLTemplateElement} */ (context.querySelector(selector));
    if (!template) {
      throw new Error(`Template not found: template${selector}`);
    }

    const clone = /** @type {!DocumentFragment} */ (this._document.importNode(
        template.content, true));

    // Prevent duplicate styles in the DOM. After a template has been stamped
    // for the first time, remove the clone's styles so they're not re-added.
    if (template.hasAttribute('data-stamped')) {
      this.findAll('style', clone).forEach(style => style.remove());
    }
    template.setAttribute('data-stamped', true);

    return clone;
  }

  /**
   * Resets the "stamped" state of the templates.
   */
  resetTemplates() {
    this.findAll('template[data-stamped]', this._document).forEach(t => {
      t.removeAttribute('data-stamped');
    });
  }

  /**
   * @param {string} text
   * @return {!Element}
   */
  convertMarkdownLinkSnippets(text) {
    const element = this.createElement('span');

    // Split on markdown links (e.g. [some link](https://...)).
    const parts = text.split(/\[([^\]]*?)\]\((https?:\/\/.*?)\)/g);

    while (parts.length) {
      // Pop off the same number of elements as there are capture groups.
      const [preambleText, linkText, linkHref] = parts.splice(0, 3);
      element.appendChild(this._document.createTextNode(preambleText));

      // Append link if there are any.
      if (linkText && linkHref) {
        const a = /** @type {!HTMLAnchorElement} */ (this.createElement('a'));
        a.rel = 'noopener';
        a.target = '_blank';
        a.textContent = linkText;
        a.href = (new URL(linkHref)).href;
        element.appendChild(a);
      }
    }

    return element;
  }

  /**
   * @param {string} text
   * @return {!Element}
   */
  convertMarkdownCodeSnippets(text) {
    const element = this.createElement('span');

    const parts = text.split(/`(.*?)`/g); // Split on markdown code slashes
    while (parts.length) {
      // Pop off the same number of elements as there are capture groups.
      const [preambleText, codeText] = parts.splice(0, 2);
      element.appendChild(this._document.createTextNode(preambleText));
      if (codeText) {
        const pre = /** @type {!HTMLPreElement} */ (this.createElement('code'));
        pre.textContent = codeText;
        element.appendChild(pre);
      }
    }

    return element;
  }

  /**
   * @return {!Document}
   */
  document() {
    return this._document;
  }

  /**
   * Guaranteed context.querySelector. Always returns an element or throws if
   * nothing matches query.
   * @param {string} query
   * @param {!Node} context
   * @return {!Element}
   */
  find(query, context) {
    const result = context.querySelector(query);
    if (result === null) {
      throw new Error(`query ${query} not found`);
    }
    return result;
  }

  /**
   * Helper for context.querySelectorAll. Returns an Array instead of a NodeList.
   * @param {string} query
   * @param {!Node} context
   * @return {!Array<!Element>}
   */
  findAll(query, context) {
    return Array.from(context.querySelectorAll(query));
  }
}

if (typeof module !== 'undefined' && module.exports) {
  module.exports = DOM;
} else {
  self.DOM = DOM;
}
;
/**
 * @license Copyright 2017 Google Inc. All Rights Reserved.
 * Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0
 * Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
 */
'use strict';

/* globals self CriticalRequestChainRenderer Util URL */

class DetailsRenderer {
  /**
   * @param {!DOM} dom
   */
  constructor(dom) {
    /** @private {!DOM} */
    this._dom = dom;
    /** @private {!Document|!Element} */
    this._templateContext; // eslint-disable-line no-unused-expressions
  }

  /**
   * @param {!Document|!Element} context
   */
  setTemplateContext(context) {
    this._templateContext = context;
  }

  /**
   * @param {!DetailsRenderer.DetailsJSON} details
   * @return {!Node}
   */
  render(details) {
    switch (details.type) {
      case 'text':
        return this._renderText(details);
      case 'url':
        return this._renderTextURL(details);
      case 'link':
        return this._renderLink(/** @type {!DetailsRenderer.LinkDetailsJSON} */ (details));
      case 'thumbnail':
        return this._renderThumbnail(/** @type {!DetailsRenderer.ThumbnailDetails} */ (details));
      case 'filmstrip':
        return this._renderFilmstrip(/** @type {!DetailsRenderer.FilmstripDetails} */ (details));
      case 'cards':
        return this._renderCards(/** @type {!DetailsRenderer.CardsDetailsJSON} */ (details));
      case 'table':
        return this._renderTable(/** @type {!DetailsRenderer.TableDetailsJSON} */ (details));
      case 'code':
        return this._renderCode(details);
      case 'node':
        return this.renderNode(/** @type {!DetailsRenderer.NodeDetailsJSON} */(details));
      case 'criticalrequestchain':
        return CriticalRequestChainRenderer.render(this._dom, this._templateContext,
          /** @type {!CriticalRequestChainRenderer.CRCDetailsJSON} */ (details));
      case 'list':
        return this._renderList(/** @type {!DetailsRenderer.ListDetailsJSON} */ (details));
      default:
        throw new Error(`Unknown type: ${details.type}`);
    }
  }

  /**
   * @param {!DetailsRenderer.DetailsJSON} text
   * @return {!Element}
   */
  _renderTextURL(text) {
    const url = text.text || '';

    let displayedPath;
    let displayedHost;
    let title;
    try {
      const parsed = Util.parseURL(url);
      displayedPath = parsed.file;
      displayedHost = `(${parsed.hostname})`;
      title = url;
    } catch (/** @type {!Error} */ e) {
      if (!(e instanceof TypeError)) {
        throw e;
      }
      displayedPath = url;
    }

    const element = this._dom.createElement('div', 'lh-text__url');
    element.appendChild(this._renderText({
      text: displayedPath,
      type: 'text',
    }));

    if (displayedHost) {
      const hostElem = this._renderText({
        text: displayedHost,
        type: 'text',
      });
      hostElem.classList.add('lh-text__url-host');
      element.appendChild(hostElem);
    }

    if (title) element.title = url;
    return element;
  }

  /**
   * @param {!DetailsRenderer.LinkDetailsJSON} details
   * @return {!Element}
   */
  _renderLink(details) {
    const allowedProtocols = ['https:', 'http:'];
    const url = new URL(details.url);
    if (!allowedProtocols.includes(url.protocol)) {
      // Fall back to text if protocol not allowed.
      return this._renderText(details);
    }

    const a = /** @type {!HTMLAnchorElement} */ (this._dom.createElement('a'));
    a.rel = 'noopener';
    a.target = '_blank';
    a.textContent = details.text;
    a.href = url.href;

    return a;
  }

  /**
   * @param {!DetailsRenderer.DetailsJSON} text
   * @return {!Element}
   */
  _renderText(text) {
    const element = this._dom.createElement('div', 'lh-text');
    element.textContent = text.text;
    return element;
  }

  /**
   * Create small thumbnail with scaled down image asset.
   * If the supplied details doesn't have an image/* mimeType, then an empty span is returned.
   * @param {!DetailsRenderer.ThumbnailDetails} value
   * @return {!Element}
   */
  _renderThumbnail(value) {
    if (/^image/.test(value.mimeType) === false) {
      return this._dom.createElement('span');
    }

    const element = this._dom.createElement('img', 'lh-thumbnail');
    element.src = value.url;
    element.alt = '';
    element.title = value.url;
    return element;
  }

  /**
   * @param {!DetailsRenderer.ListDetailsJSON} list
   * @return {!Element}
   */
  _renderList(list) {
    if (!list.items.length) return this._dom.createElement('span');

    const element = this._dom.createElement('details', 'lh-details');
    element.open = true;
    if (list.header) {
      const summary = this._dom.createElement('summary', 'lh-list__header');
      summary.textContent = list.header.text;
      element.appendChild(summary);
    }

    const itemsElem = this._dom.createChildOf(element, 'div', 'lh-list__items');
    for (const item of list.items) {
      const itemElem = this._dom.createChildOf(itemsElem, 'span', 'lh-list__item');
      itemElem.appendChild(this.render(item));
    }
    return element;
  }

  /**
   * @param {!DetailsRenderer.TableDetailsJSON} details
   * @return {!Element}
   */
  _renderTable(details) {
    if (!details.items.length) return this._dom.createElement('span');

    const element = this._dom.createElement('details', 'lh-details');
    element.open = true;
    if (details.header) {
      element.appendChild(this._dom.createElement('summary')).textContent = details.header;
    }

    const tableElem = this._dom.createChildOf(element, 'table', 'lh-table');
    const theadElem = this._dom.createChildOf(tableElem, 'thead');
    const theadTrElem = this._dom.createChildOf(theadElem, 'tr');

    for (const heading of details.itemHeaders) {
      const itemType = heading.itemType || 'text';
      const classes = `lh-table-column--${itemType}`;
      this._dom.createChildOf(theadTrElem, 'th', classes).appendChild(this.render(heading));
    }

    const tbodyElem = this._dom.createChildOf(tableElem, 'tbody');
    for (const row of details.items) {
      const rowElem = this._dom.createChildOf(tbodyElem, 'tr');
      for (const columnItem of row) {
        const classes = `lh-table-column--${columnItem.type}`;
        this._dom.createChildOf(rowElem, 'td', classes).appendChild(this.render(columnItem));
      }
    }
    return element;
  }

  /**
   * @param {!DetailsRenderer.NodeDetailsJSON} item
   * @return {!Element}
   * @protected
   */
  renderNode(item) {
    const element = this._dom.createElement('span', 'lh-node');
    element.textContent = item.snippet;
    element.title = item.selector;
    if (item.text) element.setAttribute('data-text', item.text);
    if (item.path) element.setAttribute('data-path', item.path);
    if (item.selector) element.setAttribute('data-selector', item.selector);
    if (item.snippet) element.setAttribute('data-snippet', item.snippet);
    return element;
  }

  /**
   * @param {!DetailsRenderer.CardsDetailsJSON} details
   * @return {!Element}
   */
  _renderCards(details) {
    const element = this._dom.createElement('details', 'lh-details');
    element.open = true;
    if (details.header) {
      element.appendChild(this._dom.createElement('summary')).textContent = details.header.text;
    }

    const cardsParent = this._dom.createElement('div', 'lh-scorecards');
    for (const item of details.items) {
      const card = cardsParent.appendChild(
          this._dom.createElement('div', 'lh-scorecard', {title: item.snippet}));
      const titleEl = this._dom.createElement('div', 'lh-scorecard__title');
      const valueEl = this._dom.createElement('div', 'lh-scorecard__value');
      const targetEl = this._dom.createElement('div', 'lh-scorecard__target');

      card.appendChild(titleEl).textContent = item.title;
      card.appendChild(valueEl).textContent = item.value;

      if (item.target) {
        card.appendChild(targetEl).textContent = `target: ${item.target}`;
      }
    }

    element.appendChild(cardsParent);
    return element;
  }

  /**
   * @param {!DetailsRenderer.FilmstripDetails} details
   * @return {!Element}
   */
  _renderFilmstrip(details) {
    const filmstripEl = this._dom.createElement('div', 'lh-filmstrip');

    for (const thumbnail of details.items) {
      const frameEl = this._dom.createChildOf(filmstripEl, 'div', 'lh-filmstrip__frame');

      let timing = Util.formatMilliseconds(thumbnail.timing, 1);
      if (thumbnail.timing > 1000) {
        timing = Util.formatNumber(thumbnail.timing / 1000) + ' s';
      }

      const timingEl = this._dom.createChildOf(frameEl, 'div', 'lh-filmstrip__timestamp');
      timingEl.textContent = timing;

      const base64data = thumbnail.data;
      this._dom.createChildOf(frameEl, 'img', 'lh-filmstrip__thumbnail', {
        src: `data:image/jpeg;base64,${base64data}`,
        alt: `Screenshot at ${timing}`,
      });
    }

    return filmstripEl;
  }

  /**
   * @param {!DetailsRenderer.DetailsJSON} details
   * @return {!Element}
   */
  _renderCode(details) {
    const pre = this._dom.createElement('pre', 'lh-code');
    pre.textContent = details.text;
    return pre;
  }
}

if (typeof module !== 'undefined' && module.exports) {
  module.exports = DetailsRenderer;
} else {
  self.DetailsRenderer = DetailsRenderer;
}

/**
 * @typedef {{
 *     type: string,
 *     text: (string|undefined)
 * }}
 */
DetailsRenderer.DetailsJSON; // eslint-disable-line no-unused-expressions

/**
 * @typedef {{
 *     type: string,
 *     header: ({text: string}|undefined),
 *     items: !Array<{type: string, text: (string|undefined)}>
 * }}
 */
DetailsRenderer.ListDetailsJSON; // eslint-disable-line no-unused-expressions

/**
 * @typedef {{
 *     type: string,
 *     text: (string|undefined),
 *     path: (string|undefined),
 *     selector: (string|undefined),
 *     snippet:(string|undefined)
 * }}
 */
DetailsRenderer.NodeDetailsJSON; // eslint-disable-line no-unused-expressions

/** @typedef {{
 *     type: string,
 *     header: ({text: string}|undefined),
 *     items: !Array<{title: string, value: string, snippet: (string|undefined), target: string}>
 * }}
 */
DetailsRenderer.CardsDetailsJSON; // eslint-disable-line no-unused-expressions

/**
 * @typedef {{
 *     type: string,
 *     itemType: (string|undefined),
 *     text: (string|undefined)
 * }}
 */
DetailsRenderer.TableHeaderJSON; // eslint-disable-line no-unused-expressions

/**
 * @typedef {{
 *     type: string,
 *     text: (string|undefined),
 *     path: (string|undefined),
 *     selector: (string|undefined),
 *     snippet:(string|undefined)
 * }}
 */
DetailsRenderer.NodeDetailsJSON; // eslint-disable-line no-unused-expressions

/** @typedef {{
 *     type: string,
 *     header: ({text: string}|undefined),
 *     items: !Array<!Array<!DetailsRenderer.DetailsJSON>>,
 *     itemHeaders: !Array<!DetailsRenderer.TableHeaderJSON>
 * }}
 */
DetailsRenderer.TableDetailsJSON; // eslint-disable-line no-unused-expressions

/** @typedef {{
 *     type: string,
 *     url: ({text: string}|undefined),
 *     mimeType: ({text: string}|undefined)
 * }}
 */
DetailsRenderer.ThumbnailDetails; // eslint-disable-line no-unused-expressions

/** @typedef {{
 *     type: string,
 *     url: string,
 *     text: string
 * }}
 */
DetailsRenderer.LinkDetailsJSON; // eslint-disable-line no-unused-expressions

/** @typedef {{
 *     type: string,
 *     scale: number,
 *     items: !Array<{timing: number, timestamp: number, data: string}>,
 * }}
 */
DetailsRenderer.FilmstripDetails; // eslint-disable-line no-unused-expressions
;
/**
 * @license Copyright 2017 Google Inc. All Rights Reserved.
 * Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0
 * Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
 */
'use strict';

/**
 * @fileoverview This file contains helpers for constructing and rendering the
 * critical request chains network tree.
 */

/* globals self Util */

class CriticalRequestChainRenderer {
  /**
   * Create render context for critical-request-chain tree display.
   * @param {!Object<string, !CriticalRequestChainRenderer.CRCNode>} tree
   * @return {{tree: !Object<string, !CriticalRequestChainRenderer.CRCNode>, startTime: number, transferSize: number}}
   */
  static initTree(tree) {
    let startTime = 0;
    const rootNodes = Object.keys(tree);
    if (rootNodes.length > 0) {
      const node = tree[rootNodes[0]];
      startTime = node.request.startTime;
    }

    return {tree, startTime, transferSize: 0};
  }

  /**
   * Helper to create context for each critical-request-chain node based on its
   * parent. Calculates if this node is the last child, whether it has any
   * children itself and what the tree looks like all the way back up to the root,
   * so the tree markers can be drawn correctly.
   * @param {!Object<string, !CriticalRequestChainRenderer.CRCNode>} parent
   * @param {string} id
   * @param {number} startTime
   * @param {number} transferSize
   * @param {!Array<boolean>=} treeMarkers
   * @param {boolean=} parentIsLastChild
   * @return {!CriticalRequestChainRenderer.CRCSegment}
   */
  static createSegment(parent, id, startTime, transferSize, treeMarkers, parentIsLastChild) {
    const node = parent[id];
    const siblings = Object.keys(parent);
    const isLastChild = siblings.indexOf(id) === (siblings.length - 1);
    const hasChildren = Object.keys(node.children).length > 0;

    // Copy the tree markers so that we don't change by reference.
    const newTreeMarkers = Array.isArray(treeMarkers) ? treeMarkers.slice(0) : [];

    // Add on the new entry.
    if (typeof parentIsLastChild !== 'undefined') {
      newTreeMarkers.push(!parentIsLastChild);
    }

    return {
      node,
      isLastChild,
      hasChildren,
      startTime,
      transferSize: transferSize + node.request.transferSize,
      treeMarkers: newTreeMarkers,
    };
  }

  /**
   * Creates the DOM for a tree segment.
   * @param {!DOM} dom
   * @param {!DocumentFragment} tmpl
   * @param {!CriticalRequestChainRenderer.CRCSegment} segment
   * @return {!Node}
   */
  static createChainNode(dom, tmpl, segment) {
    const chainsEl = dom.cloneTemplate('#tmpl-lh-crc__chains', tmpl);

    // Hovering over request shows full URL.
    dom.find('.crc-node', chainsEl).setAttribute('title', segment.node.request.url);

    const treeMarkeEl = dom.find('.crc-node__tree-marker', chainsEl);

    // Construct lines and add spacers for sub requests.
    segment.treeMarkers.forEach(separator => {
      if (separator) {
        treeMarkeEl.appendChild(dom.createElement('span', 'tree-marker vert'));
        treeMarkeEl.appendChild(dom.createElement('span', 'tree-marker'));
      } else {
        treeMarkeEl.appendChild(dom.createElement('span', 'tree-marker'));
        treeMarkeEl.appendChild(dom.createElement('span', 'tree-marker'));
      }
    });

    if (segment.isLastChild) {
      treeMarkeEl.appendChild(dom.createElement('span', 'tree-marker up-right'));
      treeMarkeEl.appendChild(dom.createElement('span', 'tree-marker right'));
    } else {
      treeMarkeEl.appendChild(dom.createElement('span', 'tree-marker vert-right'));
      treeMarkeEl.appendChild(dom.createElement('span', 'tree-marker right'));
    }

    if (segment.hasChildren) {
      treeMarkeEl.appendChild(dom.createElement('span', 'tree-marker horiz-down'));
    } else {
      treeMarkeEl.appendChild(dom.createElement('span', 'tree-marker right'));
    }

    // Fill in url, host, and request size information.
    const {file, hostname} = Util.parseURL(segment.node.request.url);
    const treevalEl = dom.find('.crc-node__tree-value', chainsEl);
    dom.find('.crc-node__tree-file', treevalEl).textContent = `${file}`;
    dom.find('.crc-node__tree-hostname', treevalEl).textContent = `(${hostname})`;

    if (!segment.hasChildren) {
      const span = dom.createElement('span', 'crc-node__chain-duration');
      span.textContent = ' - ' + Util.chainDuration(
          segment.node.request.startTime, segment.node.request.endTime) + 'ms, ';
      const span2 = dom.createElement('span', 'crc-node__chain-duration');
      span2.textContent = Util.formatBytesToKB(segment.node.request.transferSize);

      treevalEl.appendChild(span);
      treevalEl.appendChild(span2);
    }

    return chainsEl;
  }

  /**
   * Recursively builds a tree from segments.
   * @param {!DOM} dom
   * @param {!DocumentFragment} tmpl
   * @param {!CriticalRequestChainRenderer.CRCSegment} segment
   * @param {!Element} detailsEl Parent details element.
   * @param {!CriticalRequestChainRenderer.CRCDetailsJSON} details
   */
  static buildTree(dom, tmpl, segment, detailsEl, details) {
    detailsEl.appendChild(CriticalRequestChainRenderer.createChainNode(dom, tmpl, segment));

    for (const key of Object.keys(segment.node.children)) {
      const childSegment = CriticalRequestChainRenderer.createSegment(segment.node.children, key,
         segment.startTime, segment.transferSize, segment.treeMarkers, segment.isLastChild);
      CriticalRequestChainRenderer.buildTree(dom, tmpl, childSegment, detailsEl, details);
    }
  }

  /**
   * @param {!DOM} dom
   * @param {!Node} templateContext
   * @param {!CriticalRequestChainRenderer.CRCDetailsJSON} details
   * @return {!Node}
   */
  static render(dom, templateContext, details) {
    const tmpl = dom.cloneTemplate('#tmpl-lh-crc', templateContext);

    // Fill in top summary.
    dom.find('.lh-crc__longest_duration', tmpl).textContent =
        Util.formatNumber(details.longestChain.duration) + 'ms';
    dom.find('.lh-crc__longest_length', tmpl).textContent = details.longestChain.length;
    dom.find('.lh-crc__longest_transfersize', tmpl).textContent =
        Util.formatBytesToKB(details.longestChain.transferSize);

    const detailsEl = dom.find('.lh-details', tmpl);
    detailsEl.open = true;

    dom.find('.lh-details > summary', tmpl).textContent = details.header.text;

    // Construct visual tree.
    const root = CriticalRequestChainRenderer.initTree(details.chains);
    for (const key of Object.keys(root.tree)) {
      const segment = CriticalRequestChainRenderer.createSegment(root.tree, key,
          root.startTime, root.transferSize);
      CriticalRequestChainRenderer.buildTree(dom, tmpl, segment, detailsEl, details);
    }

    return tmpl;
  }
}

// Allow Node require()'ing.
if (typeof module !== 'undefined' && module.exports) {
  module.exports = CriticalRequestChainRenderer;
} else {
  self.CriticalRequestChainRenderer = CriticalRequestChainRenderer;
}

/** @typedef {{
 *     type: string,
 *     header: {text: string},
 *     longestChain: {duration: number, length: number, transferSize: number},
 *     chains: !Object<string, !CriticalRequestChainRenderer.CRCNode>
 * }}
 */
CriticalRequestChainRenderer.CRCDetailsJSON; // eslint-disable-line no-unused-expressions

/** @typedef {{
 *     endTime: number,
 *     responseReceivedTime: number,
 *     startTime: number,
 *     transferSize: number,
 *     url: string
 * }}
 */
CriticalRequestChainRenderer.CRCRequest; // eslint-disable-line no-unused-expressions

/**
 * Record type so children can circularly have CRCNode values.
 * @struct
 * @record
 */
CriticalRequestChainRenderer.CRCNode = function() {};

/** @type {!Object<string, !CriticalRequestChainRenderer.CRCNode>} */
CriticalRequestChainRenderer.CRCNode.prototype.children; // eslint-disable-line no-unused-expressions

/** @type {!CriticalRequestChainRenderer.CRCRequest} */
CriticalRequestChainRenderer.CRCNode.prototype.request; // eslint-disable-line no-unused-expressions

/** @typedef {{
 *     node: !CriticalRequestChainRenderer.CRCNode,
 *     isLastChild: boolean,
 *     hasChildren: boolean,
 *     startTime: number,
 *     transferSize: number,
 *     treeMarkers: !Array<boolean>
 * }}
 */
CriticalRequestChainRenderer.CRCSegment; // eslint-disable-line no-unused-expressions
;
/**
 * @license Copyright 2017 Google Inc. All Rights Reserved.
 * Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0
 * Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
 */
// @ts-nocheck
'use strict';

/* global URL */

/**
 * Generate a filenamePrefix of hostname_YYYY-MM-DD_HH-MM-SS
 * Date/time uses the local timezone, however Node has unreliable ICU
 * support, so we must construct a YYYY-MM-DD date format manually. :/
 * @param {{url: string, generatedTime: string}} results
 * @return {string}
 */
function getFilenamePrefix(results) {
  const hostname = new (URLConstructor || URL)(results.url).hostname;
  const date = (results.generatedTime && new Date(results.generatedTime)) || new Date();

  const timeStr = date.toLocaleTimeString('en-US', {hour12: false});
  const dateParts = date.toLocaleDateString('en-US', {
    year: 'numeric', month: '2-digit', day: '2-digit',
  }).split('/');
  dateParts.unshift(dateParts.pop());
  const dateStr = dateParts.join('-');

  const filenamePrefix = `${hostname}_${dateStr}_${timeStr}`;
  // replace characters that are unfriendly to filenames
  return filenamePrefix.replace(/[/?<>\\:*|":]/g, '-');
}

let URLConstructor;
if (typeof module !== 'undefined' && module.exports) {
  URLConstructor = require('./url-shim');

  module.exports = {getFilenamePrefix};
}
;
/**
 * @license Copyright 2017 Google Inc. All Rights Reserved.
 * Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0
 * Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
 */
'use strict';

/**
 * Logs messages via a UI butter.
 */
class Logger {
  /**
   * @param {!Element} element
   */
  constructor(element) {
    /** @type {!Element} */
    this.el = element;
    /** @private {?number} */
    this._id = null;
  }

  /**
   * Shows a butter bar.
   * @param {!string} msg The message to show.
   * @param {boolean=} autoHide True to hide the message after a duration.
   *     Default is true.
   */
  log(msg, autoHide = true) {
    clearTimeout(this._id);

    this.el.textContent = msg;
    this.el.classList.add('show');
    if (autoHide) {
      this._id = setTimeout(_ => {
        this.el.classList.remove('show');
      }, 7000);
    }
  }

  /**
   * @param {string} msg
   */
  warn(msg) {
    this.log('Warning: ' + msg);
  }

  /**
   * @param {string} msg
   */
  error(msg) {
    this.log(msg);
  }

  /**
   * Explicitly hides the butter bar.
   */
  hide() {
    clearTimeout(this._id);
    this.el.classList.remove('show');
  }
}

if (typeof module !== 'undefined' && module.exports) {
  module.exports = Logger;
}
;
/**
 * @license Copyright 2017 Google Inc. All Rights Reserved.
 * Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0
 * Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
 */
'use strict';

/**
 * @fileoverview Adds export button, print, and other dynamic functionality to
 * the report.
 */

/* globals self URL Blob CustomEvent getFilenamePrefix window */

class ReportUIFeatures {
  /**
   * @param {!DOM} dom
   */
  constructor(dom) {
    /** @type {!ReportRenderer.ReportJSON} */
    this.json; // eslint-disable-line no-unused-expressions
    /** @protected {!DOM} */
    this._dom = dom;
    /** @protected {!Document} */
    this._document = this._dom.document();
    /** @private {boolean} */
    this._copyAttempt = false;
    /** @type {!Element} **/
    this.exportButton; // eslint-disable-line no-unused-expressions

    this.onMediaQueryChange = this.onMediaQueryChange.bind(this);
    this.onCopy = this.onCopy.bind(this);
    this.onExportButtonClick = this.onExportButtonClick.bind(this);
    this.onExport = this.onExport.bind(this);
    this.onKeyDown = this.onKeyDown.bind(this);
    this.printShortCutDetect = this.printShortCutDetect.bind(this);
  }

  /**
   * Adds export button, print, and other functionality to the report. The method
   * should be called whenever the report needs to be re-rendered.
   * @param {!ReportRenderer.ReportJSON} report
   */
  initFeatures(report) {
    this.json = report;
    this._setupMediaQueryListeners();
    this._setupExportButton();
    this._setUpCollapseDetailsAfterPrinting();
    this._resetUIState();
    this._document.addEventListener('keydown', this.printShortCutDetect);
    this._document.addEventListener('copy', this.onCopy);
  }

  /**
   * Fires a custom DOM event on target.
   * @param {string} name Name of the event.
   * @param {!Node=} target DOM node to fire the event on.
   * @param {*=} detail Custom data to include.
   */
  _fireEventOn(name, target = this._document, detail) {
    const event = new CustomEvent(name, detail ? {detail} : null);
    target.dispatchEvent(event);
  }

  _setupMediaQueryListeners() {
    const mediaQuery = self.matchMedia('(max-width: 600px)');
    mediaQuery.addListener(this.onMediaQueryChange);
    // Ensure the handler is called on init
    this.onMediaQueryChange(mediaQuery);
  }

  /**
   * Handle media query change events.
   * @param {!MediaQueryList} mql
   */
  onMediaQueryChange(mql) {
    const root = this._dom.find('.lh-root', this._document);
    root.classList.toggle('lh-narrow', mql.matches);
  }

  _setupExportButton() {
    this.exportButton = this._dom.find('.lh-export__button', this._document);
    this.exportButton.addEventListener('click', this.onExportButtonClick);

    const dropdown = this._dom.find('.lh-export__dropdown', this._document);
    dropdown.addEventListener('click', this.onExport);
  }

  /**
   * Handle copy events.
   * @param {!Event} e
   */
  onCopy(e) {
    // Only handle copy button presses (e.g. ignore the user copying page text).
    if (this._copyAttempt) {
      // We want to write our own data to the clipboard, not the user's text selection.
      e.preventDefault();
      e.clipboardData.setData('text/plain', JSON.stringify(this.json, null, 2));

      this._fireEventOn('lh-log', this._document, {
        cmd: 'log', msg: 'Report JSON copied to clipboard',
      });
    }

    this._copyAttempt = false;
  }

  /**
   * Copies the report JSON to the clipboard (if supported by the browser).
   * @suppress {reportUnknownTypes}
   */
  onCopyButtonClick() {
    this._fireEventOn('lh-analytics', this._document, {
      cmd: 'send',
      fields: {hitType: 'event', eventCategory: 'report', eventAction: 'copy'},
    });

    try {
      if (this._document.queryCommandSupported('copy')) {
        this._copyAttempt = true;

        // Note: In Safari 10.0.1, execCommand('copy') returns true if there's
        // a valid text selection on the page. See http://caniuse.com/#feat=clipboard.
        if (!this._document.execCommand('copy')) {
          this._copyAttempt = false; // Prevent event handler from seeing this as a copy attempt.

          this._fireEventOn('lh-log', this._document, {
            cmd: 'warn', msg: 'Your browser does not support copy to clipboard.',
          });
        }
      }
    } catch (/** @type {!Error} */ e) {
      this._copyAttempt = false;
      this._fireEventOn('lh-log', this._document, {cmd: 'log', msg: e.message});
    }
  }

  closeExportDropdown() {
    this.exportButton.classList.remove('active');
  }

  /**
   * Click handler for export button.
   * @param {!Event} e
   */
  onExportButtonClick(e) {
    e.preventDefault();
    const el = /** @type {!Element} */ (e.target);
    el.classList.toggle('active');
    this._document.addEventListener('keydown', this.onKeyDown);
  }

  /**
   * Resets the state of page before capturing the page for export.
   * When the user opens the exported HTML page, certain UI elements should
   * be in their closed state (not opened) and the templates should be unstamped.
   */
  _resetUIState() {
    this.closeExportDropdown();
    this._dom.resetTemplates();
  }

  /**
   * Handler for "export as" button.
   * @param {!Event} e
   */
  onExport(e) {
    e.preventDefault();

    const el = /** @type {!Element} */ (e.target);

    if (!el.hasAttribute('data-action')) {
      return;
    }

    switch (el.getAttribute('data-action')) {
      case 'copy':
        this.onCopyButtonClick();
        break;
      case 'print-summary':
        this.collapseAllDetails();
        this.closeExportDropdown();
        self.print();
        break;
      case 'print-expanded':
        this.expandAllDetails();
        this.closeExportDropdown();
        self.print();
        break;
      case 'save-json': {
        const jsonStr = JSON.stringify(this.json, null, 2);
        this._saveFile(new Blob([jsonStr], {type: 'application/json'}));
        break;
      }
      case 'save-html': {
        const htmlStr = this.getReportHtml();
        try {
          this._saveFile(new Blob([htmlStr], {type: 'text/html'}));
        } catch (/** @type {!Error} */ e) {
          this._fireEventOn('lh-log', this._document, {
            cmd: 'error', msg: 'Could not export as HTML. ' + e.message,
          });
        }
        break;
      }
      case 'open-viewer': {
        this.sendJsonReport();
        break;
      }
      case 'save-gist': {
        this.saveAsGist();
        break;
      }
    }

    this.closeExportDropdown();
    this._document.removeEventListener('keydown', this.onKeyDown);
  }

  /**
   * Keydown handler for the document.
   * @param {!Event} e
   */
  onKeyDown(e) {
    if (e.keyCode === 27) { // ESC
      this.closeExportDropdown();
    }
  }

  /**
   * Opens a new tab to the online viewer and sends the local page's JSON results
   * to the online viewer using postMessage.
   * @protected
   */
  sendJsonReport() {
    const VIEWER_ORIGIN = 'https://googlechrome.github.io';
    const VIEWER_URL = `${VIEWER_ORIGIN}/lighthouse/viewer/`;

    // Chrome doesn't allow us to immediately postMessage to a popup right
    // after it's created. Normally, we could also listen for the popup window's
    // load event, however it is cross-domain and won't fire. Instead, listen
    // for a message from the target app saying "I'm open".
    const json = this.json;
    window.addEventListener('message', function msgHandler(/** @type {!Event} */ e) {
      const messageEvent = /** @type {!MessageEvent<{opened: boolean}>} */ (e);
      if (messageEvent.origin !== VIEWER_ORIGIN) {
        return;
      }

      if (messageEvent.data.opened) {
        popup.postMessage({lhresults: json}, VIEWER_ORIGIN);
        window.removeEventListener('message', msgHandler);
      }
    });

    const popup = /** @type {!Window} */ (window.open(VIEWER_URL, '_blank'));
  }

  /**
   * Expands audit details when user prints via keyboard shortcut.
   * @param {!Event} e
   */
  printShortCutDetect(e) {
    if ((e.ctrlKey || e.metaKey) && e.keyCode === 80) { // Ctrl+P
      this.closeExportDropdown();
    }
  }

  /**
   * Expands all audit `<details>`.
   * Ideally, a print stylesheet could take care of this, but CSS has no way to
   * open a `<details>` element.
   */
  expandAllDetails() {
    const details = this._dom.findAll('.lh-categories details', this._document);
    details.map(detail => detail.open = true);
  }

  /**
   * Collapses all audit `<details>`.
   * open a `<details>` element.
   */
  collapseAllDetails() {
    const details = this._dom.findAll('.lh-categories details', this._document);
    details.map(detail => detail.open = false);
  }

  /**
   * Sets up listeners to collapse audit `<details>` when the user closes the
   * print dialog, all `<details>` are collapsed.
   */
  _setUpCollapseDetailsAfterPrinting() {
    // FF and IE implement these old events.
    if ('onbeforeprint' in self) {
      self.addEventListener('afterprint', this.collapseAllDetails);
    } else {
      // Note: FF implements both window.onbeforeprint and media listeners. However,
      // it doesn't matchMedia doesn't fire when matching 'print'.
      self.matchMedia('print').addListener(mql => {
        if (mql.matches) {
          this.expandAllDetails();
        } else {
          this.collapseAllDetails();
        }
      });
    }
  }

  /**
   * Returns the html that recreates this report.
   * @return {string}
   * @protected
   */
  getReportHtml() {
    this._resetUIState();
    return this._document.documentElement.outerHTML;
  }

  /**
   * Save json as a gist. Unimplemented in base UI features.
   * @protected
   */
  saveAsGist() {
    throw new Error('Cannot save as gist from base report');
  }

  /**
   * Downloads a file (blob) using a[download].
   * @param {!Blob|!File} blob The file to save.
   * @private
   */
  _saveFile(blob) {
    const filename = getFilenamePrefix({
      url: this.json.url,
      generatedTime: this.json.generatedTime,
    });

    const ext = blob.type.match('json') ? '.json' : '.html';
    const href = URL.createObjectURL(blob);

    const a = /** @type {!HTMLAnchorElement} */ (this._dom.createElement('a'));
    a.download = `${filename}${ext}`;
    a.href = href;
    this._document.body.appendChild(a); // Firefox requires anchor to be in the DOM.
    a.click();

    // cleanup.
    this._document.body.removeChild(a);
    setTimeout(_ => URL.revokeObjectURL(href), 500);
  }
}

if (typeof module !== 'undefined' && module.exports) {
  module.exports = ReportUIFeatures;
} else {
  self.ReportUIFeatures = ReportUIFeatures;
}
;
/**
 * @license Copyright 2017 Google Inc. All Rights Reserved.
 * Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0
 * Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
 */
'use strict';

/* globals self, Util */

class CategoryRenderer {
  /**
   * @param {!DOM} dom
   * @param {!DetailsRenderer} detailsRenderer
   */
  constructor(dom, detailsRenderer) {
    /** @protected {!DOM} */
    this.dom = dom;
    /** @protected {!DetailsRenderer} */
    this.detailsRenderer = detailsRenderer;
    /** @protected {!Document|!Element} */
    this.templateContext = this.dom.document();

    this.detailsRenderer.setTemplateContext(this.templateContext);
  }

  /**
   * @param {!ReportRenderer.AuditJSON} audit
   * @return {!Element}
   */
  _renderAuditScore(audit) {
    const tmpl = this.dom.cloneTemplate('#tmpl-lh-audit-score', this.templateContext);

    const scoringMode = audit.result.scoringMode;
    const description = audit.result.helpText;
    let title = audit.result.description;

    if (audit.result.displayValue) {
      title += `:  ${audit.result.displayValue}`;
    }

    if (audit.result.debugString) {
      const debugStrEl = tmpl.appendChild(this.dom.createElement('div', 'lh-debug'));
      debugStrEl.textContent = audit.result.debugString;
    }

    // Append audit details to header section so the entire audit is within a <details>.
    const header = /** @type {!HTMLDetailsElement} */ (this.dom.find('.lh-score__header', tmpl));
    if (audit.result.details) {
      header.appendChild(this.detailsRenderer.render(audit.result.details));
    }

    const scoreEl = this.dom.find('.lh-score', tmpl);
    if (audit.result.informative) {
      scoreEl.classList.add('lh-score--informative');
    }
    if (audit.result.manual) {
      scoreEl.classList.add('lh-score--manual');
    }

    return this._populateScore(tmpl, audit.score, scoringMode, title, description);
  }

  /**
   * @param {!DocumentFragment|!Element} element DOM node to populate with values.
   * @param {number} score
   * @param {string} scoringMode
   * @param {string} title
   * @param {string} description
   * @return {!Element}
   */
  _populateScore(element, score, scoringMode, title, description) {
    // Fill in the blanks.
    const valueEl = this.dom.find('.lh-score__value', element);
    valueEl.textContent = Util.formatNumber(score);
    valueEl.classList.add(`lh-score__value--${Util.calculateRating(score)}`,
        `lh-score__value--${scoringMode}`);

    this.dom.find('.lh-score__title', element).appendChild(
        this.dom.convertMarkdownCodeSnippets(title));
    this.dom.find('.lh-score__description', element)
        .appendChild(this.dom.convertMarkdownLinkSnippets(description));

    return /** @type {!Element} **/ (element);
  }

  /**
   * @param {!ReportRenderer.CategoryJSON} category
   * @return {!Element}
   */
  renderCategoryScore(category) {
    const tmpl = this.dom.cloneTemplate('#tmpl-lh-category-score', this.templateContext);
    const score = Math.round(category.score);

    const gaugeContainerEl = this.dom.find('.lh-score__gauge', tmpl);
    const gaugeEl = this.renderScoreGauge(category);
    gaugeContainerEl.appendChild(gaugeEl);

    return this._populateScore(tmpl, score, 'numeric', category.name, category.description);
  }

  /**
   * @param {!ReportRenderer.AuditJSON} audit
   * @return {!Element}
   */
  renderAudit(audit) {
    const element = this.dom.createElement('div', 'lh-audit');
    element.appendChild(this._renderAuditScore(audit));
    return element;
  }

  /**
   * Renders the group container for a group of audits. Individual audit elements can be added
   * directly to the returned element.
   * @param {!ReportRenderer.GroupJSON} group
   * @param {{expandable: boolean}} opts
   * @return {!Element}
   */
  renderAuditGroup(group, opts) {
    const expandable = opts.expandable;
    const element = this.dom.createElement(expandable ? 'details' : 'div', 'lh-audit-group');
    const summmaryEl = this.dom.createChildOf(element, 'summary', 'lh-audit-group__summary');
    const headerEl = this.dom.createChildOf(summmaryEl, 'div', 'lh-audit-group__header');
    this.dom.createChildOf(summmaryEl, 'div',
      `lh-toggle-arrow  ${expandable ? '' : ' lh-toggle-arrow-unexpandable'}`, {
        title: 'See audits',
      });

    if (group.description) {
      const auditGroupDescription = this.dom.createElement('div', 'lh-audit-group__description');
      auditGroupDescription.appendChild(this.dom.convertMarkdownLinkSnippets(group.description));
      element.appendChild(auditGroupDescription);
    }
    headerEl.textContent = group.title;

    return element;
  }

  /**
   * Find the total number of audits contained within a section.
   * Accounts for nested subsections like Accessibility.
   * @param {!Array<!Element>} elements
   * @return {number}
   */
  _getTotalAuditsLength(elements) {
    // Create a scratch element to append sections to so we can reuse querySelectorAll().
    const scratch = this.dom.createElement('div');
    elements.forEach(function(element) {
      scratch.appendChild(element);
    });
    const subAudits = scratch.querySelectorAll('.lh-audit');
    if (subAudits.length) {
      return subAudits.length;
    } else {
      return elements.length;
    }
  }

  /**
   * @param {!Array<!Element>} elements
   * @return {!Element}
   */
  _renderFailedAuditsSection(elements) {
    const failedElem = this.renderAuditGroup({
      title: `${this._getTotalAuditsLength(elements)} Failed Audits`,
    }, {expandable: false});
    failedElem.classList.add('lh-failed-audits');
    elements.forEach(elem => failedElem.appendChild(elem));
    return failedElem;
  }

  /**
   * @param {!Array<!Element>} elements
   * @return {!Element}
   */
  renderPassedAuditsSection(elements) {
    const passedElem = this.renderAuditGroup({
      title: `${this._getTotalAuditsLength(elements)} Passed Audits`,
    }, {expandable: true});
    passedElem.classList.add('lh-passed-audits');
    elements.forEach(elem => passedElem.appendChild(elem));
    return passedElem;
  }

  /**
   * @param {!Array<!Element>} elements
   * @return {!Element}
   */
  _renderNotApplicableAuditsSection(elements) {
    const notApplicableElem = this.renderAuditGroup({
      title: `${this._getTotalAuditsLength(elements)} Not Applicable Audits`,
    }, {expandable: true});
    notApplicableElem.classList.add('lh-audit-group--notapplicable');
    elements.forEach(elem => notApplicableElem.appendChild(elem));
    return notApplicableElem;
  }

  /**
   * @param {!Array<!ReportRenderer.AuditJSON>} manualAudits
   * @param {!Object<string, !ReportRenderer.GroupJSON>} groupDefinitions
   * @param {!Element} element Parent container to add the manual audits to.
   */
  _renderManualAudits(manualAudits, groupDefinitions, element) {
    const auditsGroupedByGroup = /** @type {!Object<string,
        !Array<!ReportRenderer.AuditJSON>>} */ ({});
    manualAudits.forEach(audit => {
      const group = auditsGroupedByGroup[audit.group] || [];
      group.push(audit);
      auditsGroupedByGroup[audit.group] = group;
    });

    Object.keys(auditsGroupedByGroup).forEach(groupId => {
      const group = groupDefinitions[groupId];
      const auditGroupElem = this.renderAuditGroup(group, {expandable: true});
      auditGroupElem.classList.add('lh-audit-group--manual');

      auditsGroupedByGroup[groupId].forEach(audit => {
        auditGroupElem.appendChild(this.renderAudit(audit));
      });

      element.appendChild(auditGroupElem);
    });
  }

  /**
   * @param {!Document|!Element} context
   */
  setTemplateContext(context) {
    this.templateContext = context;
    this.detailsRenderer.setTemplateContext(context);
  }

  /**
   * @param {!ReportRenderer.CategoryJSON} category
   * @return {!DocumentFragment}
   */
  renderScoreGauge(category) {
    const tmpl = this.dom.cloneTemplate('#tmpl-lh-gauge', this.templateContext);
    this.dom.find('.lh-gauge__wrapper', tmpl).href = `#${category.id}`;
    this.dom.find('.lh-gauge__label', tmpl).textContent = category.name;

    const score = Math.round(category.score);
    const fillRotation = Math.floor((score / 100) * 180);

    const gauge = this.dom.find('.lh-gauge', tmpl);
    gauge.setAttribute('data-progress', score); // .dataset not supported in jsdom.
    gauge.classList.add(`lh-gauge--${Util.calculateRating(score)}`);

    this.dom.findAll('.lh-gauge__fill', gauge).forEach(el => {
      el.style.transform = `rotate(${fillRotation}deg)`;
    });

    this.dom.find('.lh-gauge__mask--full', gauge).style.transform =
        `rotate(${fillRotation}deg)`;
    this.dom.find('.lh-gauge__fill--fix', gauge).style.transform =
        `rotate(${fillRotation * 2}deg)`;
    this.dom.find('.lh-gauge__percentage', gauge).textContent = score;

    return tmpl;
  }

  /**
   * @param {!ReportRenderer.CategoryJSON} category
   * @param {!Object<string, !ReportRenderer.GroupJSON>} groupDefinitions
   * @return {!Element}
   */
  render(category, groupDefinitions) {
    const element = this.dom.createElement('div', 'lh-category');
    this.createPermalinkSpan(element, category.id);
    element.appendChild(this.renderCategoryScore(category));

    const manualAudits = category.audits.filter(audit => audit.result.manual);
    const nonManualAudits = category.audits.filter(audit => !manualAudits.includes(audit));

    const auditsGroupedByGroup = /** @type {!Object<string,
      {passed: !Array<!ReportRenderer.AuditJSON>,
      failed: !Array<!ReportRenderer.AuditJSON>,
      notApplicable: !Array<!ReportRenderer.AuditJSON>}>} */ ({});
    const auditsUngrouped = {passed: [], failed: [], notApplicable: []};

    nonManualAudits.forEach(audit => {
      let group;

      if (audit.group) {
        const groupId = audit.group;

        if (auditsGroupedByGroup[groupId]) {
          group = auditsGroupedByGroup[groupId];
        } else {
          group = {passed: [], failed: [], notApplicable: []};
          auditsGroupedByGroup[groupId] = group;
        }
      } else {
        group = auditsUngrouped;
      }

      if (audit.result.notApplicable) {
        group.notApplicable.push(audit);
      } else if (audit.score === 100 && !audit.result.debugString) {
        group.passed.push(audit);
      } else {
        group.failed.push(audit);
      }
    });

    const failedElements = /** @type {!Array<!Element>} */ ([]);
    const passedElements = /** @type {!Array<!Element>} */ ([]);
    const notApplicableElements = /** @type {!Array<!Element>} */ ([]);

    auditsUngrouped.failed.forEach((/** @type {!ReportRenderer.AuditJSON} */ audit) =>
      failedElements.push(this.renderAudit(audit)));
    auditsUngrouped.passed.forEach((/** @type {!ReportRenderer.AuditJSON} */ audit) =>
      passedElements.push(this.renderAudit(audit)));
    auditsUngrouped.notApplicable.forEach((/** @type {!ReportRenderer.AuditJSON} */ audit) =>
      notApplicableElements.push(this.renderAudit(audit)));

    let hasFailedGroups = false;

    Object.keys(auditsGroupedByGroup).forEach(groupId => {
      const group = groupDefinitions[groupId];
      const groups = auditsGroupedByGroup[groupId];

      if (groups.failed.length) {
        const auditGroupElem = this.renderAuditGroup(group, {expandable: false});
        groups.failed.forEach(item => auditGroupElem.appendChild(this.renderAudit(item)));
        auditGroupElem.open = true;
        failedElements.push(auditGroupElem);

        hasFailedGroups = true;
      }

      if (groups.passed.length) {
        const auditGroupElem = this.renderAuditGroup(group, {expandable: true});
        groups.passed.forEach(item => auditGroupElem.appendChild(this.renderAudit(item)));
        passedElements.push(auditGroupElem);
      }

      if (groups.notApplicable.length) {
        const auditGroupElem = this.renderAuditGroup(group, {expandable: true});
        groups.notApplicable.forEach(item => auditGroupElem.appendChild(this.renderAudit(item)));
        notApplicableElements.push(auditGroupElem);
      }
    });

    if (failedElements.length) {
      // if failed audits are grouped skip the 'X Failed Audits' header
      if (hasFailedGroups) {
        failedElements.forEach(elem => element.appendChild(elem));
      } else {
        const failedElem = this._renderFailedAuditsSection(failedElements);
        element.appendChild(failedElem);
      }
    }

    if (passedElements.length) {
      const passedElem = this.renderPassedAuditsSection(passedElements);
      element.appendChild(passedElem);
    }

    if (notApplicableElements.length) {
      const notApplicableElem = this._renderNotApplicableAuditsSection(notApplicableElements);
      element.appendChild(notApplicableElem);
    }

    // Render manual audits after passing.
    this._renderManualAudits(manualAudits, groupDefinitions, element);

    return element;
  }

  /**
   * Create a non-semantic span used for hash navigation of categories
   * @param {!Element} element
   * @param {string} id
   */
  createPermalinkSpan(element, id) {
    const permalinkEl = this.dom.createChildOf(element, 'span', 'lh-permalink');
    permalinkEl.id = id;
  }
}

if (typeof module !== 'undefined' && module.exports) {
  module.exports = CategoryRenderer;
} else {
  self.CategoryRenderer = CategoryRenderer;
}
;
/**
 * @license Copyright 2018 Google Inc. All Rights Reserved.
 * Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0
 * Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
 */
'use strict';

/* globals self, Util, CategoryRenderer */

class PerformanceCategoryRenderer extends CategoryRenderer {
  /**
   * @param {!ReportRenderer.AuditJSON} audit
   * @param {number} scale
   * @return {!Element}
   */
  _renderTimelineMetricAudit(audit, scale) {
    const tmpl = this.dom.cloneTemplate('#tmpl-lh-timeline-metric', this.templateContext);
    const element = this.dom.find('.lh-timeline-metric', tmpl);
    element.classList.add(`lh-timeline-metric--${Util.calculateRating(audit.score)}`);

    const titleEl = this.dom.find('.lh-timeline-metric__title', tmpl);
    titleEl.textContent = audit.result.description;

    const valueEl = this.dom.find('.lh-timeline-metric__value', tmpl);
    valueEl.textContent = audit.result.displayValue;

    const descriptionEl = this.dom.find('.lh-timeline-metric__description', tmpl);
    descriptionEl.appendChild(this.dom.convertMarkdownLinkSnippets(audit.result.helpText));

    if (typeof audit.result.rawValue !== 'number') {
      const debugStrEl = this.dom.createChildOf(element, 'div', 'lh-debug');
      debugStrEl.textContent = audit.result.debugString || 'Report error: no metric information';
      return element;
    }

    const sparklineBarEl = this.dom.find('.lh-sparkline__bar', tmpl);
    sparklineBarEl.style.width = `${audit.result.rawValue / scale * 100}%`;

    return element;
  }

  /**
   * @param {!ReportRenderer.AuditJSON} audit
   * @param {number} scale
   * @return {!Element}
   */
  _renderPerfHintAudit(audit, scale) {
    const extendedInfo = /** @type {!PerformanceCategoryRenderer.PerfHintExtendedInfo}
        */ (audit.result.extendedInfo);
    const tooltipAttrs = {title: audit.result.displayValue};

    const element = this.dom.createElement('details', [
      'lh-perf-hint',
      `lh-perf-hint--${Util.calculateRating(audit.score)}`,
      'lh-expandable-details',
    ].join(' '));

    const summary = this.dom.createChildOf(element, 'summary', 'lh-perf-hint__summary ' +
      'lh-expandable-details__summary');
    const titleEl = this.dom.createChildOf(summary, 'div', 'lh-perf-hint__title');
    titleEl.textContent = audit.result.description;

    this.dom.createChildOf(summary, 'div', 'lh-toggle-arrow', {title: 'See resources'});

    if (!extendedInfo || typeof audit.result.rawValue !== 'number') {
      const debugStrEl = this.dom.createChildOf(summary, 'div', 'lh-debug');
      debugStrEl.textContent = audit.result.debugString || 'Report error: no extended information';
      return element;
    }

    const sparklineContainerEl = this.dom.createChildOf(summary, 'div', 'lh-perf-hint__sparkline',
        tooltipAttrs);
    const sparklineEl = this.dom.createChildOf(sparklineContainerEl, 'div', 'lh-sparkline');
    const sparklineBarEl = this.dom.createChildOf(sparklineEl, 'div', 'lh-sparkline__bar');
    sparklineBarEl.style.width = audit.result.rawValue / scale * 100 + '%';

    const statsEl = this.dom.createChildOf(summary, 'div', 'lh-perf-hint__stats', tooltipAttrs);
    const statsMsEl = this.dom.createChildOf(statsEl, 'div', 'lh-perf-hint__primary-stat');
    statsMsEl.textContent = Util.formatMilliseconds(audit.result.rawValue);

    if (extendedInfo.value.wastedKb) {
      const statsKbEl = this.dom.createChildOf(statsEl, 'div', 'lh-perf-hint__secondary-stat');
      statsKbEl.textContent = Util.formatNumber(extendedInfo.value.wastedKb) + ' KB';
    }

    const descriptionEl = this.dom.createChildOf(element, 'div', 'lh-perf-hint__description');
    descriptionEl.appendChild(this.dom.convertMarkdownLinkSnippets(audit.result.helpText));

    if (audit.result.debugString) {
      const debugStrEl = this.dom.createChildOf(summary, 'div', 'lh-debug');
      debugStrEl.textContent = audit.result.debugString;
    }

    if (audit.result.details) {
      element.appendChild(this.detailsRenderer.render(audit.result.details));
    }

    return element;
  }

  /**
   * @override
   */
  render(category, groups) {
    const element = this.dom.createElement('div', 'lh-category');
    this.createPermalinkSpan(element, category.id);
    element.appendChild(this.renderCategoryScore(category));

    const metricAudits = category.audits.filter(audit => audit.group === 'perf-metric');
    const metricAuditsEl = this.renderAuditGroup(groups['perf-metric'], {expandable: false});
    const timelineContainerEl = this.dom.createChildOf(metricAuditsEl, 'div',
        'lh-timeline-container');
    const timelineEl = this.dom.createChildOf(timelineContainerEl, 'div', 'lh-timeline');

    let perfTimelineScale = 0;
    metricAudits.forEach(audit => {
      if (typeof audit.result.rawValue === 'number' && audit.result.rawValue) {
        perfTimelineScale = Math.max(perfTimelineScale, audit.result.rawValue);
      }
    });

    const thumbnailAudit = category.audits.find(audit => audit.id === 'screenshot-thumbnails');
    const thumbnailResult = thumbnailAudit && thumbnailAudit.result;
    if (thumbnailResult && thumbnailResult.details) {
      const thumbnailDetails = /** @type {!DetailsRenderer.FilmstripDetails} */
          (thumbnailResult.details);
      perfTimelineScale = Math.max(perfTimelineScale, thumbnailDetails.scale);
      const filmstripEl = this.detailsRenderer.render(thumbnailDetails);
      timelineEl.appendChild(filmstripEl);
    }

    metricAudits.forEach(item => {
      if (item.id === 'speed-index-metric' || item.id === 'estimated-input-latency') {
        return metricAuditsEl.appendChild(this.renderAudit(item));
      }

      timelineEl.appendChild(this._renderTimelineMetricAudit(item, perfTimelineScale));
    });

    metricAuditsEl.open = true;
    element.appendChild(metricAuditsEl);

    const hintAudits = category.audits
        .filter(audit => audit.group === 'perf-hint' && audit.score < 100)
        .sort((auditA, auditB) => auditB.result.rawValue - auditA.result.rawValue);
    if (hintAudits.length) {
      const maxWaste = Math.max(...hintAudits.map(audit => audit.result.rawValue));
      const scale = Math.ceil(maxWaste / 1000) * 1000;
      const hintAuditsEl = this.renderAuditGroup(groups['perf-hint'], {expandable: false});
      hintAudits.forEach(item => hintAuditsEl.appendChild(this._renderPerfHintAudit(item, scale)));
      hintAuditsEl.open = true;
      element.appendChild(hintAuditsEl);
    }

    const infoAudits = category.audits
        .filter(audit => audit.group === 'perf-info' && audit.score < 100);
    if (infoAudits.length) {
      const infoAuditsEl = this.renderAuditGroup(groups['perf-info'], {expandable: false});
      infoAudits.forEach(item => infoAuditsEl.appendChild(this.renderAudit(item)));
      infoAuditsEl.open = true;
      element.appendChild(infoAuditsEl);
    }

    const passedElements = category.audits
        .filter(audit => (audit.group === 'perf-hint' || audit.group === 'perf-info') &&
            audit.score === 100)
        .map(audit => this.renderAudit(audit));

    if (!passedElements.length) return element;

    const passedElem = this.renderPassedAuditsSection(passedElements);
    element.appendChild(passedElem);
    return element;
  }
}

if (typeof module !== 'undefined' && module.exports) {
  module.exports = PerformanceCategoryRenderer;
} else {
  self.PerformanceCategoryRenderer = PerformanceCategoryRenderer;
}

/**
 * @typedef {{
 *     value: {
 *       wastedMs: (number|undefined),
 *       wastedKb: (number|undefined),
 *     }
 * }}
 */
PerformanceCategoryRenderer.PerfHintExtendedInfo; // eslint-disable-line no-unused-expressions
;
/**
 * @license Copyright 2017 Google Inc. All Rights Reserved.
 * Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0
 * Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
 */
'use strict';

/**
 * @fileoverview The entry point for rendering the Lighthouse report based on the JSON output.
 *    This file is injected into the report HTML along with the JSON report.
 *
 * Dummy text for ensuring report robustness: \u003c/script> pre$`post %%LIGHTHOUSE_JSON%%
 */

/* globals self, Util, DetailsRenderer, CategoryRenderer, PerformanceCategoryRenderer */

class ReportRenderer {
  /**
   * @param {!DOM} dom
   */
  constructor(dom) {
    /** @private {!DOM} */
    this._dom = dom;
    /** @private {!Document|!Element} */
    this._templateContext = this._dom.document();
  }

  /**
   * @param {!ReportRenderer.ReportJSON} report
   * @param {!Element} container Parent element to render the report into.
   */
  renderReport(report, container) {
    container.textContent = ''; // Remove previous report.
    const element = container.appendChild(this._renderReport(report));

    return /** @type {!Element} **/ (element);
  }

  /**
   * Define a custom element for <templates> to be extracted from. For example:
   *     this.setTemplateContext(new DOMParser().parseFromString(htmlStr, 'text/html'))
   * @param {!Document|!Element} context
   */
  setTemplateContext(context) {
    this._templateContext = context;
  }

  /**
   * @param {!ReportRenderer.ReportJSON} report
   * @return {!DocumentFragment}
   */
  _renderReportHeader(report) {
    const header = this._dom.cloneTemplate('#tmpl-lh-heading', this._templateContext);
    this._dom.find('.lh-config__timestamp', header).textContent =
        Util.formatDateTime(report.generatedTime);
    const url = this._dom.find('.lh-metadata__url', header);
    url.href = report.url;
    url.textContent = report.url;

    this._dom.find('.lh-env__item__ua', header).textContent = report.userAgent;

    const env = this._dom.find('.lh-env__items', header);
    report.runtimeConfig.environment.forEach(runtime => {
      const item = this._dom.cloneTemplate('#tmpl-lh-env__items', env);
      this._dom.find('.lh-env__name', item).textContent = runtime.name;
      this._dom.find('.lh-env__description', item).textContent = runtime.description;
      this._dom.find('.lh-env__enabled', item).textContent =
          runtime.enabled ? 'Enabled' : 'Disabled';
      env.appendChild(item);
    });

    return header;
  }

  /**
   * @param {!ReportRenderer.ReportJSON} report
   * @return {!DocumentFragment}
   */
  _renderReportFooter(report) {
    const footer = this._dom.cloneTemplate('#tmpl-lh-footer', this._templateContext);
    this._dom.find('.lh-footer__version', footer).textContent = report.lighthouseVersion;
    this._dom.find('.lh-footer__timestamp', footer).textContent =
        Util.formatDateTime(report.generatedTime);
    return footer;
  }

  /**
   * @param {!ReportRenderer.ReportJSON} report
   * @return {!DocumentFragment}
   */
  _renderReportNav(report) {
    const leftNav = this._dom.cloneTemplate('#tmpl-lh-leftnav', this._templateContext);

    this._dom.find('.leftnav__header__version', leftNav).textContent =
        `Version: ${report.lighthouseVersion}`;

    const nav = this._dom.find('.lh-leftnav', leftNav);
    for (const category of report.reportCategories) {
      const itemsTmpl = this._dom.cloneTemplate('#tmpl-lh-leftnav__items', leftNav);

      const navItem = this._dom.find('.lh-leftnav__item', itemsTmpl);
      navItem.href = `#${category.id}`;

      this._dom.find('.leftnav-item__category', navItem).textContent = category.name;
      const score = this._dom.find('.leftnav-item__score', navItem);
      score.classList.add(`lh-score__value--${Util.calculateRating(category.score)}`);
      score.textContent = Math.round(category.score);
      nav.appendChild(navItem);
    }
    return leftNav;
  }

  /**
   * Returns a div with a list of top-level warnings, or an empty div if no warnings.
   * @param {!ReportRenderer.ReportJSON} report
   * @return {!Node}
   */
  _renderReportWarnings(report) {
    if (!report.runWarnings || report.runWarnings.length === 0) {
      return this._dom.createElement('div');
    }

    const container = this._dom.cloneTemplate('#tmpl-lh-run-warnings', this._templateContext);
    const warnings = this._dom.find('ul', container);
    for (const warningString of report.runWarnings) {
      const warning = warnings.appendChild(this._dom.createElement('li'));
      warning.textContent = warningString;
    }

    return container;
  }

  /**
   * @param {!ReportRenderer.ReportJSON} report
   * @return {!Element}
   */
  _renderReport(report) {
    const container = this._dom.createElement('div', 'lh-container');
    container.appendChild(this._renderReportHeader(report)); // sticky header goes at the top.
    container.appendChild(this._renderReportNav(report));
    const reportSection = container.appendChild(this._dom.createElement('div', 'lh-report'));

    reportSection.appendChild(this._renderReportWarnings(report));

    let scoreHeader;
    const isSoloCategory = report.reportCategories.length === 1;
    if (!isSoloCategory) {
      scoreHeader = reportSection.appendChild(this._dom.createElement('div', 'lh-scores-header'));
    }

    const detailsRenderer = new DetailsRenderer(this._dom);
    const categoryRenderer = new CategoryRenderer(this._dom, detailsRenderer);
    categoryRenderer.setTemplateContext(this._templateContext);
    const perfCategoryRenderer = new PerformanceCategoryRenderer(this._dom, detailsRenderer);
    perfCategoryRenderer.setTemplateContext(this._templateContext);

    const categories = reportSection.appendChild(this._dom.createElement('div', 'lh-categories'));
    for (const category of report.reportCategories) {
      if (scoreHeader) {
        scoreHeader.appendChild(categoryRenderer.renderScoreGauge(category));
      }

      let renderer = categoryRenderer;

      if (category.id === 'performance') {
        renderer = perfCategoryRenderer;
      }

      categories.appendChild(renderer.render(category, report.reportGroups));
    }

    reportSection.appendChild(this._renderReportFooter(report));

    return container;
  }
}

if (typeof module !== 'undefined' && module.exports) {
  module.exports = ReportRenderer;
} else {
  self.ReportRenderer = ReportRenderer;
}

/**
 * @typedef {{
 *     id: string,
 *     weight: number,
 *     score: number,
 *     group: string,
 *     result: {
 *       rawValue: (number|undefined),
 *       description: string,
 *       informative: boolean,
 *       manual: boolean,
 *       notApplicable: boolean,
 *       debugString: string,
 *       displayValue: string,
 *       helpText: string,
 *       score: (number|boolean),
 *       scoringMode: string,
 *       extendedInfo: Object,
 *       details: (!DetailsRenderer.DetailsJSON|undefined)
 *     }
 * }}
 */
ReportRenderer.AuditJSON; // eslint-disable-line no-unused-expressions

/**
 * @typedef {{
 *     name: string,
 *     id: string,
 *     weight: number,
 *     score: number,
 *     description: string,
 *     audits: !Array<!ReportRenderer.AuditJSON>
 * }}
 */
ReportRenderer.CategoryJSON; // eslint-disable-line no-unused-expressions

/**
 * @typedef {{
 *     title: string,
 *     description: (string|undefined),
 * }}
 */
ReportRenderer.GroupJSON; // eslint-disable-line no-unused-expressions

/**
 * @typedef {{
 *     lighthouseVersion: string,
 *     userAgent: string,
 *     generatedTime: string,
 *     timing: {total: number},
 *     initialUrl: string,
 *     url: string,
 *     runWarnings: (!Array<string>|undefined),
 *     artifacts: {traces: !Object},
 *     reportCategories: !Array<!ReportRenderer.CategoryJSON>,
 *     reportGroups: !Object<string, !ReportRenderer.GroupJSON>,
 *     runtimeConfig: {
 *       blockedUrlPatterns: !Array<string>,
 *       extraHeaders: !Object,
 *       environment: !Array<{description: string, enabled: boolean, name: string}>
 *     }
 * }}
 */
ReportRenderer.ReportJSON; // eslint-disable-line no-unused-expressions
</script>
  <script>window.__LIGHTHOUSE_JSON__ = {"userAgent":"Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/66.0.3359.139 Safari/537.36","lighthouseVersion":"2.9.3","generatedTime":"2018-05-06T07:10:58.544Z","initialUrl":"https://facebookfeed-neel.firebaseapp.com/","url":"https://facebookfeed-neel.firebaseapp.com/","runWarnings":[],"audits":{"is-on-https":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"value":[]},"scoringMode":"binary","name":"is-on-https","description":"Uses HTTPS","helpText":"All sites should be protected with HTTPS, even ones that don't handle sensitive data. HTTPS prevents intruders from tampering with or passively listening in on the communications between your app and your users, and is a prerequisite for HTTP/2 and many new web platform APIs. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/https).","details":{"type":"list","header":{"type":"text","text":"Insecure URLs:"},"items":[]}},"redirects-http":{"score":true,"displayValue":"","rawValue":true,"scoringMode":"binary","name":"redirects-http","description":"Redirects HTTP traffic to HTTPS","helpText":"If you've already set up HTTPS, make sure that you redirect all HTTP traffic to HTTPS. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/http-redirects-to-https)."},"service-worker":{"score":true,"displayValue":"","rawValue":true,"scoringMode":"binary","name":"service-worker","description":"Registers a service worker","helpText":"The service worker is the technology that enables your app to use many Progressive Web App features, such as offline, add to homescreen, and push notifications. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/registered-service-worker)."},"works-offline":{"score":true,"displayValue":"","rawValue":true,"scoringMode":"binary","name":"works-offline","description":"Responds with a 200 when offline","helpText":"If you're building a Progressive Web App, consider using a service worker so that your app can work offline. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/http-200-when-offline)."},"viewport":{"score":true,"displayValue":"","rawValue":true,"debugString":"","scoringMode":"binary","name":"viewport","description":"Has a `\u003cmeta name=\"viewport\">` tag with `width` or `initial-scale`","helpText":"Add a viewport meta tag to optimize your app for mobile screens. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/has-viewport-meta-tag)."},"without-javascript":{"score":true,"displayValue":"","rawValue":true,"scoringMode":"binary","name":"without-javascript","description":"Contains some content when JavaScript is not available","helpText":"Your app should display some content when JavaScript is disabled, even if it's just a warning to the user that JavaScript is required to use the app. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/no-js)."},"first-meaningful-paint":{"score":94,"displayValue":"1,790 ms","rawValue":1790.1,"extendedInfo":{"value":{"timestamps":{"navStart":1486179379511,"fCP":1486181169577,"fMP":1486181169579,"onLoad":1486183845564,"endOfTrace":1486200178379},"timings":{"navStart":0,"fCP":1790.066,"fMP":1790.068,"onLoad":4466.053,"endOfTrace":20798.868},"fmpFellBack":false}},"scoringMode":"numeric","name":"first-meaningful-paint","description":"First meaningful paint","helpText":"First meaningful paint measures when the primary content of a page is visible. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/first-meaningful-paint)."},"load-fast-enough-for-pwa":{"score":true,"displayValue":"","rawValue":true,"debugString":"First Interactive was found at 4,500 ms; however, the network request latencies were not sufficiently realistic, so the performance measurements cannot be trusted.","extendedInfo":{"value":{"areLatenciesAll3G":false,"firstRequestLatencies":[{"url":"https://facebookfeed-neel.firebaseapp.com/","latency":"564.35"},{"url":"https://fonts.googleapis.com/css?family=Roboto:400,700","latency":"571.17"},{"url":"https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css","latency":"583.66"},{"url":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu4mxKKTU1Kg.woff2","latency":"630.16"},{"url":"https://facebookfeed-neel.firebaseio.com/posts.json","latency":"585.11"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c","latency":"0.2"},{"url":"chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/wrs_env.js","latency":"0.04"}],"isFast":true,"timeToFirstInteractive":4502.306}},"scoringMode":"binary","name":"load-fast-enough-for-pwa","description":"Page load is fast enough on 3G","helpText":"A fast page load over a 3G network ensures a good mobile user experience. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/fast-3g).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Latency (ms)"}],"items":[[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/"},{"type":"text","text":"564.35"}],[{"type":"url","text":"https://fonts.googleapis.com/css?family=Roboto:400,700"},{"type":"text","text":"571.17"}],[{"type":"url","text":"https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css"},{"type":"text","text":"583.66"}],[{"type":"url","text":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu4mxKKTU1Kg.woff2"},{"type":"text","text":"630.16"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseio.com/posts.json"},{"type":"text","text":"585.11"}],[{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c"},{"type":"text","text":"0.2"}],[{"type":"url","text":"chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/wrs_env.js"},{"type":"text","text":"0.04"}]]}},"speed-index-metric":{"score":null,"displayValue":"","rawValue":null,"error":true,"debugString":"Audit error: Images have different sizes!","scoringMode":"numeric","name":"speed-index-metric","description":"Perceptual Speed Index","helpText":"Speed Index shows how quickly the contents of a page are visibly populated. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/speed-index)."},"screenshot-thumbnails":{"score":null,"displayValue":"","rawValue":null,"error":true,"debugString":"Audit error: Images have different sizes!","scoringMode":"binary","informative":true,"name":"screenshot-thumbnails","description":"Screenshot Thumbnails","helpText":"This is what the load of your site looked like."},"estimated-input-latency":{"score":100,"displayValue":"16 ms","rawValue":16,"extendedInfo":{"value":[{"percentile":0.5,"time":16},{"percentile":0.75,"time":16},{"percentile":0.9,"time":16},{"percentile":0.99,"time":81.81819999999644},{"percentile":1,"time":208.29499999998006}]},"scoringMode":"numeric","name":"estimated-input-latency","description":"Estimated Input Latency","helpText":"The score above is an estimate of how long your app takes to respond to user input, in milliseconds. There is a 90% probability that a user encounters this amount of latency, or less. 10% of the time a user can expect additional latency. If your latency is higher than 50 ms, users may perceive your app as laggy. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/estimated-input-latency)."},"errors-in-console":{"score":true,"displayValue":"","rawValue":0,"scoringMode":"binary","name":"errors-in-console","description":"No browser errors logged to the console","helpText":"Errors logged to the console indicate unresolved problems. They can come from network request failures and other browser concerns.","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"code","text":"Description"}],"items":[]}},"time-to-first-byte":{"score":true,"displayValue":"560 ms","rawValue":564.345,"debugString":"","extendedInfo":{"value":{"wastedMs":-35.65499999999997}},"scoringMode":"binary","informative":true,"name":"time-to-first-byte","description":"Keep server response times low (TTFB)","helpText":"Time To First Byte identifies the time at which your server sends a response. [Learn more](https://developers.google.com/web/tools/chrome-devtools/network-performance/issues)."},"first-interactive":{"score":84,"displayValue":"4,500 ms","rawValue":4502.306,"extendedInfo":{"value":{"timeInMs":4502.306,"timestamp":1486183881817}},"scoringMode":"numeric","name":"first-interactive","description":"First Interactive (beta)","helpText":"First Interactive marks the time at which the page is minimally interactive. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/first-interactive)."},"consistently-interactive":{"score":84,"displayValue":"4,500 ms","rawValue":4502.306,"extendedInfo":{"value":{"cpuQuietPeriod":{"start":1486183881.817,"end":1486200178.379},"networkQuietPeriod":{"start":1486183528.4919999,"end":1486200178.379},"cpuQuietPeriods":[{"start":1486183881.817,"end":1486200178.379}],"networkQuietPeriods":[{"start":1486183528.4919999,"end":1486200178.379}],"timestamp":1486183881817,"timeInMs":4502.306}},"scoringMode":"numeric","name":"consistently-interactive","description":"Consistently Interactive (beta)","helpText":"Consistently Interactive marks the time at which the page is fully interactive. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/consistently-interactive)."},"user-timings":{"score":true,"displayValue":"0","rawValue":true,"extendedInfo":{"value":[]},"scoringMode":"binary","informative":true,"name":"user-timings","description":"User Timing marks and measures","helpText":"Consider instrumenting your app with the User Timing API to create custom, real-world measurements of key user experiences. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/user-timing).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"text","text":"Name"},{"type":"text","itemType":"text","text":"Type"},{"type":"text","itemType":"text","text":"Time"}],"items":[]}},"critical-request-chains":{"score":false,"displayValue":"15","rawValue":false,"extendedInfo":{"value":{"chains":{"34A2F958E8DA35C4C3C68A28746FC5F7":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/","startTime":1486179.383232,"endTime":1486179.966296,"responseReceivedTime":1486179.9554990001,"transferSize":1855},"children":{"15080.62":{"request":{"url":"https://fonts.googleapis.com/css?family=Roboto:400,700","startTime":1486180.072954,"endTime":1486180.904868,"responseReceivedTime":1486180.647064,"transferSize":681},"children":{}},"15080.63":{"request":{"url":"https://fonts.googleapis.com/icon?family=Material+Icons","startTime":1486180.073977,"endTime":1486180.909894,"responseReceivedTime":1486180.654143,"transferSize":372},"children":{}},"15080.64":{"request":{"url":"https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css","startTime":1486180.07529,"endTime":1486180.914856,"responseReceivedTime":1486180.661993,"transferSize":18885},"children":{}},"15080.65":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/css/app.css","startTime":1486180.083797,"endTime":1486180.923173,"responseReceivedTime":1486180.670025,"transferSize":207},"children":{}},"15080.66":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/css/feed.css","startTime":1486180.084763,"endTime":1486180.927271,"responseReceivedTime":1486180.678015,"transferSize":639},"children":{}},"15080.69":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/promise.js","startTime":1486180.678962,"endTime":1486181.266579,"responseReceivedTime":1486181.258414,"transferSize":2448},"children":{}},"15080.70":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/fetch.js","startTime":1486180.775301,"endTime":1486181.409872,"responseReceivedTime":1486181.3534960002,"transferSize":3426},"children":{}},"15080.71":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/idb.js","startTime":1486180.775458,"endTime":1486181.401772,"responseReceivedTime":1486181.3614909998,"transferSize":1858},"children":{}},"15080.72":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/utility.js","startTime":1486180.775576,"endTime":1486181.370249,"responseReceivedTime":1486181.3694820001,"transferSize":785},"children":{}},"15080.73":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/app.js","startTime":1486180.775682,"endTime":1486181.397222,"responseReceivedTime":1486181.395681,"transferSize":1323},"children":{}},"15080.74":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/feed.js","startTime":1486180.775786,"endTime":1486181.417822,"responseReceivedTime":1486181.396312,"transferSize":2933},"children":{}},"15080.89":{"request":{"url":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu4mxKKTU1Kg.woff2","startTime":1486181.128047,"endTime":1486181.909994,"responseReceivedTime":1486181.760324,"transferSize":10814},"children":{}},"15080.97":{"request":{"url":"https://fonts.gstatic.com/s/materialicons/v36/flUhRq6tzZclQEJ-Vdg-IuiaDsNcIhQ8tQ.woff2","startTime":1486181.134527,"endTime":1486182.395296,"responseReceivedTime":1486181.760996,"transferSize":49172},"children":{}},"15080.88":{"request":{"url":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu7GxKKTU1Kvnz.woff2","startTime":1486182.275052,"endTime":1486182.975742,"responseReceivedTime":1486182.895545,"transferSize":8118},"children":{}},"15080.87":{"request":{"url":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu7WxKKTU1Kvnz.woff2","startTime":1486183.015248,"endTime":1486183.67418,"responseReceivedTime":1486183.643009,"transferSize":3375},"children":{}}}}},"longestChain":{"duration":4290.948000038043,"length":2,"transferSize":3375}}},"scoringMode":"binary","informative":true,"name":"critical-request-chains","description":"Critical Request Chains","helpText":"The Critical Request Chains below show you what resources are issued with a high priority. Consider reducing the length of chains, reducing the download size of resources, or deferring the download of unnecessary resources to improve page load. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/critical-request-chains).","details":{"type":"criticalrequestchain","header":{"type":"text","text":"View critical network waterfall:"},"chains":{"34A2F958E8DA35C4C3C68A28746FC5F7":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/","startTime":1486179.383232,"endTime":1486179.966296,"responseReceivedTime":1486179.9554990001,"transferSize":1855},"children":{"15080.62":{"request":{"url":"https://fonts.googleapis.com/css?family=Roboto:400,700","startTime":1486180.072954,"endTime":1486180.904868,"responseReceivedTime":1486180.647064,"transferSize":681},"children":{}},"15080.63":{"request":{"url":"https://fonts.googleapis.com/icon?family=Material+Icons","startTime":1486180.073977,"endTime":1486180.909894,"responseReceivedTime":1486180.654143,"transferSize":372},"children":{}},"15080.64":{"request":{"url":"https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css","startTime":1486180.07529,"endTime":1486180.914856,"responseReceivedTime":1486180.661993,"transferSize":18885},"children":{}},"15080.65":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/css/app.css","startTime":1486180.083797,"endTime":1486180.923173,"responseReceivedTime":1486180.670025,"transferSize":207},"children":{}},"15080.66":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/css/feed.css","startTime":1486180.084763,"endTime":1486180.927271,"responseReceivedTime":1486180.678015,"transferSize":639},"children":{}},"15080.69":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/promise.js","startTime":1486180.678962,"endTime":1486181.266579,"responseReceivedTime":1486181.258414,"transferSize":2448},"children":{}},"15080.70":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/fetch.js","startTime":1486180.775301,"endTime":1486181.409872,"responseReceivedTime":1486181.3534960002,"transferSize":3426},"children":{}},"15080.71":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/idb.js","startTime":1486180.775458,"endTime":1486181.401772,"responseReceivedTime":1486181.3614909998,"transferSize":1858},"children":{}},"15080.72":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/utility.js","startTime":1486180.775576,"endTime":1486181.370249,"responseReceivedTime":1486181.3694820001,"transferSize":785},"children":{}},"15080.73":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/app.js","startTime":1486180.775682,"endTime":1486181.397222,"responseReceivedTime":1486181.395681,"transferSize":1323},"children":{}},"15080.74":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/feed.js","startTime":1486180.775786,"endTime":1486181.417822,"responseReceivedTime":1486181.396312,"transferSize":2933},"children":{}},"15080.89":{"request":{"url":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu4mxKKTU1Kg.woff2","startTime":1486181.128047,"endTime":1486181.909994,"responseReceivedTime":1486181.760324,"transferSize":10814},"children":{}},"15080.97":{"request":{"url":"https://fonts.gstatic.com/s/materialicons/v36/flUhRq6tzZclQEJ-Vdg-IuiaDsNcIhQ8tQ.woff2","startTime":1486181.134527,"endTime":1486182.395296,"responseReceivedTime":1486181.760996,"transferSize":49172},"children":{}},"15080.88":{"request":{"url":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu7GxKKTU1Kvnz.woff2","startTime":1486182.275052,"endTime":1486182.975742,"responseReceivedTime":1486182.895545,"transferSize":8118},"children":{}},"15080.87":{"request":{"url":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu7WxKKTU1Kvnz.woff2","startTime":1486183.015248,"endTime":1486183.67418,"responseReceivedTime":1486183.643009,"transferSize":3375},"children":{}}}}},"longestChain":{"duration":4290.948000038043,"length":2,"transferSize":3375}}},"redirects":{"score":100,"displayValue":"0 ms","rawValue":0,"extendedInfo":{"value":{"wastedMs":0}},"scoringMode":"binary","name":"redirects","description":"Avoids page redirects","helpText":"Redirects introduce additional delays before the page can be loaded. [Learn more](https://developers.google.com/speed/docs/insights/AvoidRedirects).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"text","text":"Redirected URL"},{"type":"text","itemType":"text","text":"Time for Redirect"}],"items":[]}},"webapp-install-banner":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"value":{"warnings":[],"failures":[],"manifestValues":{"isParseFailure":false,"allChecks":[{"id":"hasStartUrl","failureText":"Manifest does not contain a `start_url`","passing":true},{"id":"hasIconsAtLeast192px","failureText":"Manifest does not have icons at least 192px","passing":true},{"id":"hasIconsAtLeast512px","failureText":"Manifest does not have icons at least 512px","passing":true},{"id":"hasPWADisplayValue","failureText":"Manifest's `display` value is not one of: minimal-ui | fullscreen | standalone","passing":true},{"id":"hasBackgroundColor","failureText":"Manifest does not have `background_color`","passing":true},{"id":"hasThemeColor","failureText":"Manifest does not have `theme_color`","passing":true},{"id":"hasShortName","failureText":"Manifest does not have `short_name`","passing":true},{"id":"shortNameLength","failureText":"Manifest `short_name` will be truncated when displayed on the homescreen","passing":true},{"id":"hasName","failureText":"Manifest does not have `name`","passing":true}]}}},"scoringMode":"binary","name":"webapp-install-banner","description":"User can be prompted to Install the Web App","helpText":"Browsers can proactively prompt users to add your app to their homescreen, which can lead to higher engagement. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/install-prompt)."},"splash-screen":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"value":{"failures":[],"manifestValues":{"isParseFailure":false,"allChecks":[{"id":"hasStartUrl","failureText":"Manifest does not contain a `start_url`","passing":true},{"id":"hasIconsAtLeast192px","failureText":"Manifest does not have icons at least 192px","passing":true},{"id":"hasIconsAtLeast512px","failureText":"Manifest does not have icons at least 512px","passing":true},{"id":"hasPWADisplayValue","failureText":"Manifest's `display` value is not one of: minimal-ui | fullscreen | standalone","passing":true},{"id":"hasBackgroundColor","failureText":"Manifest does not have `background_color`","passing":true},{"id":"hasThemeColor","failureText":"Manifest does not have `theme_color`","passing":true},{"id":"hasShortName","failureText":"Manifest does not have `short_name`","passing":true},{"id":"shortNameLength","failureText":"Manifest `short_name` will be truncated when displayed on the homescreen","passing":true},{"id":"hasName","failureText":"Manifest does not have `name`","passing":true}]}}},"scoringMode":"binary","name":"splash-screen","description":"Configured for a custom splash screen","helpText":"A themed splash screen ensures a high-quality experience when users launch your app from their homescreens. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/custom-splash-screen)."},"themed-omnibox":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"value":{"failures":[],"manifestValues":{"isParseFailure":false,"allChecks":[{"id":"hasStartUrl","failureText":"Manifest does not contain a `start_url`","passing":true},{"id":"hasIconsAtLeast192px","failureText":"Manifest does not have icons at least 192px","passing":true},{"id":"hasIconsAtLeast512px","failureText":"Manifest does not have icons at least 512px","passing":true},{"id":"hasPWADisplayValue","failureText":"Manifest's `display` value is not one of: minimal-ui | fullscreen | standalone","passing":true},{"id":"hasBackgroundColor","failureText":"Manifest does not have `background_color`","passing":true},{"id":"hasThemeColor","failureText":"Manifest does not have `theme_color`","passing":true},{"id":"hasShortName","failureText":"Manifest does not have `short_name`","passing":true},{"id":"shortNameLength","failureText":"Manifest `short_name` will be truncated when displayed on the homescreen","passing":true},{"id":"hasName","failureText":"Manifest does not have `name`","passing":true}]},"themeColor":"#3f51b5"}},"scoringMode":"binary","name":"themed-omnibox","description":"Address bar matches brand colors","helpText":"The browser address bar can be themed to match your site. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/address-bar)."},"manifest-short-name-length":{"score":true,"displayValue":"","rawValue":true,"scoringMode":"binary","name":"manifest-short-name-length","description":"Manifest's `short_name` won't be truncated when displayed on homescreen","helpText":"Make your app's `short_name` fewer than 12 characters to ensure that it's not truncated on homescreens. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/manifest-short_name-is-not-truncated)."},"content-width":{"score":true,"displayValue":"","rawValue":true,"debugString":"","scoringMode":"binary","name":"content-width","description":"Content is sized correctly for the viewport","helpText":"If the width of your app's content doesn't match the width of the viewport, your app might not be optimized for mobile screens. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/content-sized-correctly-for-viewport)."},"image-aspect-ratio":{"score":true,"displayValue":"","rawValue":true,"scoringMode":"binary","name":"image-aspect-ratio","description":"Displays images with correct aspect ratio","helpText":"Image display dimensions should match natural aspect ratio.","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"thumbnail","text":""},{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Aspect Ratio (Displayed)"},{"type":"text","itemType":"text","text":"Aspect Ratio (Actual)"}],"items":[]}},"deprecations":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"value":[]},"scoringMode":"binary","name":"deprecations","description":"Avoids deprecated APIs","helpText":"Deprecated APIs will eventually be removed from the browser. [Learn more](https://www.chromestatus.com/features#deprecated).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"code","text":"Deprecation / Warning"},{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Line"}],"items":[]}},"mainthread-work-breakdown":{"score":true,"displayValue":"1,600 ms","rawValue":1596.9429988861084,"extendedInfo":{"value":{"Evaluate Script":449.4710006713867,"Recalculate Style":287.753999710083,"Compile Script":183.61499977111816,"Layout":152.54500007629395,"Parse HTML":107.49699997901917,"DOM GC":85.07699966430664,"Run Microtasks":79.31799960136414,"Minor GC":66.71499991416931,"Update Layer Tree":55.695000410079956,"Paint":41.459999561309814,"Parse Stylesheet":38.2039999961853,"Major GC":37.06899952888489,"Composite Layers":12.523000001907349}},"scoringMode":"binary","informative":true,"name":"mainthread-work-breakdown","description":"Main thread work breakdown","helpText":"Consider reducing the time spent parsing, compiling and executing JS.You may find delivering smaller JS payloads helps with this.","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"text","text":"Category"},{"type":"text","itemType":"text","text":"Work"},{"type":"text","itemType":"text","text":"Time spent"}],"items":[[{"type":"text","text":"Script Evaluation"},{"type":"text","text":"Evaluate Script"},{"type":"text","text":"449 ms"}],[{"type":"text","text":"Script Evaluation"},{"type":"text","text":"Run Microtasks"},{"type":"text","text":"79 ms"}],[{"type":"text","text":"Style & Layout"},{"type":"text","text":"Recalculate Style"},{"type":"text","text":"288 ms"}],[{"type":"text","text":"Style & Layout"},{"type":"text","text":"Layout"},{"type":"text","text":"153 ms"}],[{"type":"text","text":"Garbage collection"},{"type":"text","text":"DOM GC"},{"type":"text","text":"85 ms"}],[{"type":"text","text":"Garbage collection"},{"type":"text","text":"Minor GC"},{"type":"text","text":"67 ms"}],[{"type":"text","text":"Garbage collection"},{"type":"text","text":"Major GC"},{"type":"text","text":"37 ms"}],[{"type":"text","text":"Script Parsing & Compile"},{"type":"text","text":"Compile Script"},{"type":"text","text":"184 ms"}],[{"type":"text","text":"Parsing HTML & CSS"},{"type":"text","text":"Parse HTML"},{"type":"text","text":"107 ms"}],[{"type":"text","text":"Parsing HTML & CSS"},{"type":"text","text":"Parse Stylesheet"},{"type":"text","text":"38 ms"}],[{"type":"text","text":"Compositing"},{"type":"text","text":"Update Layer Tree"},{"type":"text","text":"56 ms"}],[{"type":"text","text":"Compositing"},{"type":"text","text":"Composite Layers"},{"type":"text","text":"13 ms"}],[{"type":"text","text":"Paint"},{"type":"text","text":"Paint"},{"type":"text","text":"41 ms"}]]}},"bootup-time":{"score":true,"displayValue":"750 ms","rawValue":746.6599998474121,"extendedInfo":{"value":{"chrome-extension://aapbdbdomjkkjkaonfhkkikfgjllcleb/bubble_compiled.js":{"Script Evaluation":102.56599998474121,"Script Parsing & Compile":89.31299996376038},"chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/ext/common.js":{"Script Evaluation":118.42399978637695,"Script Parsing & Compile":1.0329999923706055},"https://facebookfeed-neel.firebaseapp.com/":{"Parsing HTML & CSS":107.45000004768372},"https://facebookfeed-neel.firebaseapp.com/src/js/feed.js":{"Style & Layout":56.027000188827515,"Script Evaluation":6.446000099182129,"Script Parsing & Compile":5.7779998779296875},"chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/include.preload.js":{"Script Evaluation":40.31599998474121,"Script Parsing & Compile":10.980999946594238},"chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/content.js":{"Script Evaluation":46.75600028038025,"Script Parsing & Compile":1.0449998378753662},"https://facebookfeed-neel.firebaseapp.com/src/js/material.min.js":{"Style & Layout":28.432999849319458,"Script Evaluation":7.531000137329102,"Script Parsing & Compile":1.7829999923706055},"chrome-extension://fmkadmapgofadopljbjfkapdkoienihi/build/inject.js":{"Script Evaluation":7.674999952316284,"Script Parsing & Compile":7.582000017166138},"chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/notification.js":{"Script Parsing & Compile":7.745999813079834,"Script Evaluation":7.26800012588501},"chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/adblock-bandaids.js":{"Script Evaluation":9.022000074386597,"Script Parsing & Compile":4.226000070571899},"chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/wrs_env.js":{"Script Evaluation":11.585000038146973,"Script Parsing & Compile":1.5810000896453857,"Style & Layout":0.03399991989135742},"chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/browser-polyfill.js":{"Script Evaluation":6.94599986076355,"Script Parsing & Compile":5.55400013923645},"https://facebookfeed-neel.firebaseapp.com/src/js/idb.js":{"Script Evaluation":4.460999965667725,"Script Parsing & Compile":3.4110000133514404},"chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/adblock-picreplacement-contentscript-loader.js":{"Script Evaluation":6.164999961853027,"Script Parsing & Compile":0.5950000286102295},"https://facebookfeed-neel.firebaseapp.com/src/js/fetch.js":{"Script Parsing & Compile":6.11899995803833,"Script Evaluation":0.4419999122619629},"https://facebookfeed-neel.firebaseapp.com/src/js/promise.js":{"Script Parsing & Compile":4.788000106811523,"Script Evaluation":0.9969997406005859},"chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/elemHideEmulation.js":{"Script Parsing & Compile":5.049000024795532,"Script Evaluation":0.23399996757507324},"chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/adblock-functions.js":{"Script Parsing & Compile":2.628999948501587,"Script Evaluation":1.6170001029968262},"https://facebookfeed-neel.firebaseapp.com/src/js/utility.js":{"Script Evaluation":2.7930002212524414,"Script Parsing & Compile":1.2219998836517334},"https://facebookfeed-neel.firebaseapp.com/src/js/app.js":{"Script Evaluation":3.2070000171661377,"Script Parsing & Compile":0.565000057220459},"chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/ext/content.js":{"Script Evaluation":2.4630000591278076,"Script Parsing & Compile":0.6079998016357422},"chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/adblock-notificationoverlay.js":{"Script Parsing & Compile":2.2879998683929443,"Script Evaluation":0.42600011825561523},"chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/include.postload.js":{"Script Parsing & Compile":1.6110000610351562,"Script Evaluation":0.4119999408721924},"chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/adblock-uiscripts-rightclick_hook.js":{"Script Parsing & Compile":0.8050000667572021,"Script Evaluation":0.6310000419616699},"https://facebookfeed-neel.firebaseapp.com/sw.js":{"Parsing HTML & CSS":0.020999908447265625}}},"scoringMode":"binary","name":"bootup-time","description":"JavaScript boot-up time","helpText":"Consider reducing the time spent parsing, compiling, and executing JS. You may find delivering smaller JS payloads helps with this. [Learn more](https://developers.google.com/web/lighthouse/audits/bootup).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Script Evaluation"},{"type":"text","itemType":"text","text":"Script Parsing & Compile"}],"items":[[{"type":"url","text":"chrome-extension://aapbdbdomjkkjkaonfhkkikfgjllcleb/bubble_compiled.js"},{"type":"text","text":"103 ms"},{"type":"text","text":"89 ms"}],[{"type":"url","text":"chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/ext/common.js"},{"type":"text","text":"118 ms"},{"type":"text","text":"1 ms"}],[{"type":"url","text":"chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/include.preload.js"},{"type":"text","text":"40 ms"},{"type":"text","text":"11 ms"}],[{"type":"url","text":"chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/content.js"},{"type":"text","text":"47 ms"},{"type":"text","text":"1 ms"}],[{"type":"url","text":"chrome-extension://fmkadmapgofadopljbjfkapdkoienihi/build/inject.js"},{"type":"text","text":"8 ms"},{"type":"text","text":"8 ms"}],[{"type":"url","text":"chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/notification.js"},{"type":"text","text":"7 ms"},{"type":"text","text":"8 ms"}],[{"type":"url","text":"chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/adblock-bandaids.js"},{"type":"text","text":"9 ms"},{"type":"text","text":"4 ms"}],[{"type":"url","text":"chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/wrs_env.js"},{"type":"text","text":"12 ms"},{"type":"text","text":"2 ms"}],[{"type":"url","text":"chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/browser-polyfill.js"},{"type":"text","text":"7 ms"},{"type":"text","text":"6 ms"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/feed.js"},{"type":"text","text":"6 ms"},{"type":"text","text":"6 ms"}]]}},"uses-rel-preload":{"score":100,"displayValue":"0 ms","rawValue":0,"extendedInfo":{"value":[]},"scoringMode":"numeric","informative":true,"name":"uses-rel-preload","description":"Preload key requests","helpText":"Consider using \u003clink rel=preload> to prioritize fetching late-discovered resources sooner [Learn more](https://developers.google.com/web/updates/2016/03/link-rel-preload).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Potential Savings"}],"items":[]}},"font-display":{"score":true,"displayValue":"","rawValue":true,"scoringMode":"binary","name":"font-display","description":"All text remains visible during webfont loads","helpText":"Leverage the font-display CSS feature to ensure text is user-visible while webfonts are loading. [Learn more](https://developers.google.com/web/updates/2016/02/font-display).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"Font URL"},{"type":"text","itemType":"text","text":"Font download time"}],"items":[]}},"network-requests":{"score":100,"displayValue":"27","rawValue":27,"extendedInfo":{"value":[{"url":"https://facebookfeed-neel.firebaseapp.com/","startTime":0,"endTime":583.0639998894185,"transferSize":1855,"statusCode":200,"mimeType":"text/html","resourceType":"document"},{"url":"https://fonts.googleapis.com/css?family=Roboto:400,700","startTime":689.7219999227673,"endTime":1521.6359999030828,"transferSize":681,"statusCode":200,"mimeType":"text/css","resourceType":"stylesheet"},{"url":"https://fonts.googleapis.com/icon?family=Material+Icons","startTime":690.7450000289828,"endTime":1526.661999989301,"transferSize":372,"statusCode":200,"mimeType":"text/css","resourceType":"stylesheet"},{"url":"https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css","startTime":692.0580000150949,"endTime":1531.6240000538528,"transferSize":18885,"statusCode":200,"mimeType":"text/css","resourceType":"stylesheet"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/css/app.css","startTime":700.565000064671,"endTime":1539.941000053659,"transferSize":207,"statusCode":200,"mimeType":"text/css","resourceType":"stylesheet"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/css/feed.css","startTime":701.530999969691,"endTime":1544.0390000585467,"transferSize":639,"statusCode":200,"mimeType":"text/css","resourceType":"stylesheet"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png","startTime":1768.6799999792129,"endTime":4379.0539999026805,"transferSize":292040,"statusCode":200,"mimeType":"image/png","resourceType":"image"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/material.min.js","startTime":1987.2669999022037,"endTime":2766.512000001967,"transferSize":11790,"statusCode":200,"mimeType":"application/javascript","resourceType":"script"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/promise.js","startTime":1295.729999896139,"endTime":1883.3469999954104,"transferSize":2448,"statusCode":200,"mimeType":"application/javascript","resourceType":"script"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/fetch.js","startTime":1392.0690000522882,"endTime":2026.6400000546128,"transferSize":3426,"statusCode":200,"mimeType":"application/javascript","resourceType":"script"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/idb.js","startTime":1392.2259998507798,"endTime":2018.5399998445064,"transferSize":1858,"statusCode":200,"mimeType":"application/javascript","resourceType":"script"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/utility.js","startTime":1392.344000050798,"endTime":1987.0169998612255,"transferSize":785,"statusCode":200,"mimeType":"application/javascript","resourceType":"script"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/app.js","startTime":1392.4499999266118,"endTime":2013.9899998903275,"transferSize":1323,"statusCode":200,"mimeType":"application/javascript","resourceType":"script"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/feed.js","startTime":1392.5540000200272,"endTime":2034.5900000538677,"transferSize":2933,"statusCode":200,"mimeType":"application/javascript","resourceType":"script"},{"url":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu4mxKKTU1Kg.woff2","startTime":1744.8149998672307,"endTime":2526.7620000522584,"transferSize":10814,"statusCode":200,"mimeType":"font/woff2","resourceType":"font"},{"url":"https://fonts.gstatic.com/s/materialicons/v36/flUhRq6tzZclQEJ-Vdg-IuiaDsNcIhQ8tQ.woff2","startTime":1751.2949998490512,"endTime":3012.063999893144,"transferSize":49172,"statusCode":200,"mimeType":"font/woff2","resourceType":"font"},{"url":"https://facebookfeed-neel.firebaseio.com/posts.json","startTime":2071.6989999637008,"endTime":2820.968999993056,"transferSize":2515,"statusCode":200,"mimeType":"application/json","resourceType":"fetch"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c","startTime":2855.061999987811,"endTime":3683.9959998615086,"transferSize":0,"statusCode":200,"mimeType":"image/png","resourceType":"image"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&token=60c2ac2a-de60-4ebc-b970-70264d96a80b","startTime":2857.2929999791086,"endTime":3708.718999987468,"transferSize":0,"statusCode":200,"mimeType":"image/png","resourceType":"image"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0","startTime":2861.094000050798,"endTime":3773.873999947682,"transferSize":0,"statusCode":200,"mimeType":"image/png","resourceType":"image"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&token=d0181e98-3ea9-499b-865e-8cec92fa1e33","startTime":2865.482999943197,"endTime":3844.9899998959154,"transferSize":0,"statusCode":200,"mimeType":"image/png","resourceType":"image"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A42%3A19.478Z.png?alt=media&token=99f7a653-5780-411b-91c6-ca1a86b4a8a5","startTime":2868.502999888733,"endTime":3849.0140000358224,"transferSize":0,"statusCode":200,"mimeType":"image/png","resourceType":"image"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A32%3A53.884Z.png?alt=media&token=aca0478e-23b6-45d9-90d7-594641c37b77","startTime":2871.157999848947,"endTime":4056.5939999651164,"transferSize":0,"statusCode":200,"mimeType":"image/png","resourceType":"image"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A41%3A06.899Z.png?alt=media&token=ab32239e-a34f-4a94-880a-bc03dec7121b","startTime":2906.4879999496043,"endTime":4145.259999902919,"transferSize":0,"statusCode":200,"mimeType":"image/png","resourceType":"image"},{"url":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu7GxKKTU1Kvnz.woff2","startTime":2891.8200000189245,"endTime":3592.509999871254,"transferSize":8118,"statusCode":200,"mimeType":"font/woff2","resourceType":"font"},{"url":"chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/wrs_env.js","startTime":3320.219999877736,"endTime":3495.8009999245405,"transferSize":0,"statusCode":200,"mimeType":"application/javascript","resourceType":"script"},{"url":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu7WxKKTU1Kvnz.woff2","startTime":3632.0159998722374,"endTime":4290.948000038043,"transferSize":3375,"statusCode":200,"mimeType":"font/woff2","resourceType":"font"}]},"scoringMode":"binary","informative":true,"name":"network-requests","description":"Network Requests","helpText":"Lists the network requests that were made during page load.","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"ms","text":"Start Time"},{"type":"text","itemType":"ms","text":"End Time"},{"type":"text","itemType":"bytes","text":"Transfer Size"},{"type":"text","itemType":"text","text":"Status Code"},{"type":"text","itemType":"text","text":"MIME Type"},{"type":"text","itemType":"text","text":"Resource Type"}],"items":[[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/"},{"type":"ms","text":0},{"type":"ms","text":583.0639998894185},{"type":"bytes","text":1855},{"type":"text","text":200},{"type":"text","text":"text/html"},{"type":"text","text":"document"}],[{"type":"url","text":"https://fonts.googleapis.com/css?family=Roboto:400,700"},{"type":"ms","text":689.7219999227673},{"type":"ms","text":1521.6359999030828},{"type":"bytes","text":681},{"type":"text","text":200},{"type":"text","text":"text/css"},{"type":"text","text":"stylesheet"}],[{"type":"url","text":"https://fonts.googleapis.com/icon?family=Material+Icons"},{"type":"ms","text":690.7450000289828},{"type":"ms","text":1526.661999989301},{"type":"bytes","text":372},{"type":"text","text":200},{"type":"text","text":"text/css"},{"type":"text","text":"stylesheet"}],[{"type":"url","text":"https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css"},{"type":"ms","text":692.0580000150949},{"type":"ms","text":1531.6240000538528},{"type":"bytes","text":18885},{"type":"text","text":200},{"type":"text","text":"text/css"},{"type":"text","text":"stylesheet"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/css/app.css"},{"type":"ms","text":700.565000064671},{"type":"ms","text":1539.941000053659},{"type":"bytes","text":207},{"type":"text","text":200},{"type":"text","text":"text/css"},{"type":"text","text":"stylesheet"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/css/feed.css"},{"type":"ms","text":701.530999969691},{"type":"ms","text":1544.0390000585467},{"type":"bytes","text":639},{"type":"text","text":200},{"type":"text","text":"text/css"},{"type":"text","text":"stylesheet"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png"},{"type":"ms","text":1768.6799999792129},{"type":"ms","text":4379.0539999026805},{"type":"bytes","text":292040},{"type":"text","text":200},{"type":"text","text":"image/png"},{"type":"text","text":"image"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/material.min.js"},{"type":"ms","text":1987.2669999022037},{"type":"ms","text":2766.512000001967},{"type":"bytes","text":11790},{"type":"text","text":200},{"type":"text","text":"application/javascript"},{"type":"text","text":"script"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/promise.js"},{"type":"ms","text":1295.729999896139},{"type":"ms","text":1883.3469999954104},{"type":"bytes","text":2448},{"type":"text","text":200},{"type":"text","text":"application/javascript"},{"type":"text","text":"script"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/fetch.js"},{"type":"ms","text":1392.0690000522882},{"type":"ms","text":2026.6400000546128},{"type":"bytes","text":3426},{"type":"text","text":200},{"type":"text","text":"application/javascript"},{"type":"text","text":"script"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/idb.js"},{"type":"ms","text":1392.2259998507798},{"type":"ms","text":2018.5399998445064},{"type":"bytes","text":1858},{"type":"text","text":200},{"type":"text","text":"application/javascript"},{"type":"text","text":"script"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/utility.js"},{"type":"ms","text":1392.344000050798},{"type":"ms","text":1987.0169998612255},{"type":"bytes","text":785},{"type":"text","text":200},{"type":"text","text":"application/javascript"},{"type":"text","text":"script"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/app.js"},{"type":"ms","text":1392.4499999266118},{"type":"ms","text":2013.9899998903275},{"type":"bytes","text":1323},{"type":"text","text":200},{"type":"text","text":"application/javascript"},{"type":"text","text":"script"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/feed.js"},{"type":"ms","text":1392.5540000200272},{"type":"ms","text":2034.5900000538677},{"type":"bytes","text":2933},{"type":"text","text":200},{"type":"text","text":"application/javascript"},{"type":"text","text":"script"}],[{"type":"url","text":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu4mxKKTU1Kg.woff2"},{"type":"ms","text":1744.8149998672307},{"type":"ms","text":2526.7620000522584},{"type":"bytes","text":10814},{"type":"text","text":200},{"type":"text","text":"font/woff2"},{"type":"text","text":"font"}],[{"type":"url","text":"https://fonts.gstatic.com/s/materialicons/v36/flUhRq6tzZclQEJ-Vdg-IuiaDsNcIhQ8tQ.woff2"},{"type":"ms","text":1751.2949998490512},{"type":"ms","text":3012.063999893144},{"type":"bytes","text":49172},{"type":"text","text":200},{"type":"text","text":"font/woff2"},{"type":"text","text":"font"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseio.com/posts.json"},{"type":"ms","text":2071.6989999637008},{"type":"ms","text":2820.968999993056},{"type":"bytes","text":2515},{"type":"text","text":200},{"type":"text","text":"application/json"},{"type":"text","text":"fetch"}],[{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c"},{"type":"ms","text":2855.061999987811},{"type":"ms","text":3683.9959998615086},{"type":"bytes","text":0},{"type":"text","text":200},{"type":"text","text":"image/png"},{"type":"text","text":"image"}],[{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&token=60c2ac2a-de60-4ebc-b970-70264d96a80b"},{"type":"ms","text":2857.2929999791086},{"type":"ms","text":3708.718999987468},{"type":"bytes","text":0},{"type":"text","text":200},{"type":"text","text":"image/png"},{"type":"text","text":"image"}],[{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0"},{"type":"ms","text":2861.094000050798},{"type":"ms","text":3773.873999947682},{"type":"bytes","text":0},{"type":"text","text":200},{"type":"text","text":"image/png"},{"type":"text","text":"image"}],[{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&token=d0181e98-3ea9-499b-865e-8cec92fa1e33"},{"type":"ms","text":2865.482999943197},{"type":"ms","text":3844.9899998959154},{"type":"bytes","text":0},{"type":"text","text":200},{"type":"text","text":"image/png"},{"type":"text","text":"image"}],[{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A42%3A19.478Z.png?alt=media&token=99f7a653-5780-411b-91c6-ca1a86b4a8a5"},{"type":"ms","text":2868.502999888733},{"type":"ms","text":3849.0140000358224},{"type":"bytes","text":0},{"type":"text","text":200},{"type":"text","text":"image/png"},{"type":"text","text":"image"}],[{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A32%3A53.884Z.png?alt=media&token=aca0478e-23b6-45d9-90d7-594641c37b77"},{"type":"ms","text":2871.157999848947},{"type":"ms","text":4056.5939999651164},{"type":"bytes","text":0},{"type":"text","text":200},{"type":"text","text":"image/png"},{"type":"text","text":"image"}],[{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A41%3A06.899Z.png?alt=media&token=ab32239e-a34f-4a94-880a-bc03dec7121b"},{"type":"ms","text":2906.4879999496043},{"type":"ms","text":4145.259999902919},{"type":"bytes","text":0},{"type":"text","text":200},{"type":"text","text":"image/png"},{"type":"text","text":"image"}],[{"type":"url","text":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu7GxKKTU1Kvnz.woff2"},{"type":"ms","text":2891.8200000189245},{"type":"ms","text":3592.509999871254},{"type":"bytes","text":8118},{"type":"text","text":200},{"type":"text","text":"font/woff2"},{"type":"text","text":"font"}],[{"type":"url","text":"chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/wrs_env.js"},{"type":"ms","text":3320.219999877736},{"type":"ms","text":3495.8009999245405},{"type":"bytes","text":0},{"type":"text","text":200},{"type":"text","text":"application/javascript"},{"type":"text","text":"script"}],[{"type":"url","text":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu7WxKKTU1Kvnz.woff2"},{"type":"ms","text":3632.0159998722374},{"type":"ms","text":4290.948000038043},{"type":"bytes","text":3375},{"type":"text","text":200},{"type":"text","text":"font/woff2"},{"type":"text","text":"font"}]]}},"pwa-cross-browser":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"pwa-cross-browser","description":"Site works cross-browser","helpText":"To reach the most number of users, sites should work across every major browser. [Learn more](https://developers.google.com/web/progressive-web-apps/checklist#site-works-cross-browser)."},"pwa-page-transitions":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"pwa-page-transitions","description":"Page transitions don't feel like they block on the network","helpText":"Transitions should feel snappy as you tap around, even on a slow network, a key to perceived performance. [Learn more](https://developers.google.com/web/progressive-web-apps/checklist#page-transitions-dont-feel-like-they-block-on-the-network)."},"pwa-each-page-has-url":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"pwa-each-page-has-url","description":"Each page has a URL","helpText":"Ensure individual pages are deep linkable via the URLs and that URLs are unique for the purpose of shareability on social media. [Learn more](https://developers.google.com/web/progressive-web-apps/checklist#each-page-has-a-url)."},"accesskeys":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"accesskeys","description":"`[accesskey]` values are not unique","helpText":"Access keys let users quickly focus a part of the page. For proper navigation, each access key must be unique. [Learn more](https://dequeuniversity.com/rules/axe/2.2/accesskeys?application=lighthouse)."},"aria-allowed-attr":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"aria-allowed-attr","description":"`[aria-*]` attributes match their roles","helpText":"Each ARIA `role` supports a specific subset of `aria-*` attributes. Mismatching these invalidates the `aria-*` attributes. [Learn more](https://dequeuniversity.com/rules/axe/2.2/aria-allowed-attr?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"aria-required-attr":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"aria-required-attr","description":"`[role]`s have all required `[aria-*]` attributes","helpText":"Some ARIA roles have required attributes that describe the state of the element to screen readers. [Learn more](https://dequeuniversity.com/rules/axe/2.2/aria-required-attr?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"aria-required-children":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"aria-required-children","description":"Elements with `[role]` that require specific children `[role]`s, are present","helpText":"Some ARIA parent roles must contain specific child roles to perform their intended accessibility functions. [Learn more](https://dequeuniversity.com/rules/axe/2.2/aria-required-children?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"aria-required-parent":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"aria-required-parent","description":"`[role]`s are contained by their required parent element","helpText":"Some ARIA child roles must be contained by specific parent roles to properly perform their intended accessibility functions. [Learn more](https://dequeuniversity.com/rules/axe/2.2/aria-required-parent?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"aria-roles":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"aria-roles","description":"`[role]` values are valid","helpText":"ARIA roles must have valid values in order to perform their intended accessibility functions. [Learn more](https://dequeuniversity.com/rules/axe/2.2/aria-roles?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"aria-valid-attr-value":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"aria-valid-attr-value","description":"`[aria-*]` attributes have valid values","helpText":"Assistive technologies, like screen readers, can't interpret ARIA attributes with invalid values. [Learn more](https://dequeuniversity.com/rules/axe/2.2/aria-valid-attr-value?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"aria-valid-attr":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"aria-valid-attr","description":"`[aria-*]` attributes are valid and not misspelled","helpText":"Assistive technologies, like screen readers, can't interpret ARIA attributes with invalid names. [Learn more](https://dequeuniversity.com/rules/axe/2.2/aria-valid-attr?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"audio-caption":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"audio-caption","description":"`\u003caudio>` elements are missing a `\u003ctrack>` element with `[kind=\"captions\"]`.","helpText":"Captions make audio elements usable for deaf or hearing-impaired users, providing critical information such as who is talking, what they're saying, and other non-speech information. [Learn more](https://dequeuniversity.com/rules/axe/2.2/audio-caption?application=lighthouse)."},"button-name":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"button-name","description":"Buttons have an accessible name","helpText":"When a button doesn't have an accessible name, screen readers announce it as \"button\", making it unusable for users who rely on screen readers. [Learn more](https://dequeuniversity.com/rules/axe/2.2/button-name?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"bypass":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"bypass","description":"The page contains a heading, skip link, or landmark region","helpText":"Adding ways to bypass repetitive content lets keyboard users navigate the page more efficiently. [Learn more](https://dequeuniversity.com/rules/axe/2.2/bypass?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"color-contrast":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"color-contrast","description":"Background and foreground colors have a sufficient contrast ratio","helpText":"Low-contrast text is difficult or impossible for many users to read. [Learn more](https://dequeuniversity.com/rules/axe/2.2/color-contrast?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"definition-list":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"definition-list","description":"`\u003cdl>`'s do not contain only properly-ordered `\u003cdt>` and `\u003cdd>` groups, `\u003cscript>` or `\u003ctemplate>` elements.","helpText":"When definition lists are not properly marked up, screen readers may produce confusing or inaccurate output. [Learn more](https://dequeuniversity.com/rules/axe/2.2/definition-list?application=lighthouse)."},"dlitem":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"dlitem","description":"Definition list items are not wrapped in `\u003cdl>` elements","helpText":"Definition list items (`\u003cdt>` and `\u003cdd>`) must be wrapped in a parent `\u003cdl>` element to ensure that screen readers can properly announce them. [Learn more](https://dequeuniversity.com/rules/axe/2.2/dlitem?application=lighthouse)."},"document-title":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"document-title","description":"Document has a `\u003ctitle>` element","helpText":"The title gives screen reader users an overview of the page, and search engine users rely on it heavily to determine if a page is relevant to their search. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/title).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"duplicate-id":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"duplicate-id","description":"`[id]` attributes on the page are unique","helpText":"The value of an id attribute must be unique to prevent other instances from being overlooked by assistive technologies. [Learn more](https://dequeuniversity.com/rules/axe/2.2/duplicate-id?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"frame-title":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"frame-title","description":"`\u003cframe>` or `\u003ciframe>` elements do not have a title","helpText":"Screen reader users rely on frame titles to describe the contents of frames. [Learn more](https://dequeuniversity.com/rules/axe/2.2/frame-title?application=lighthouse)."},"html-has-lang":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"html-has-lang","description":"`\u003chtml>` element has a `[lang]` attribute","helpText":"If a page doesn't specify a lang attribute, a screen reader assumes that the page is in the default language that the user chose when setting up the screen reader. If the page isn't actually in the default language, then the screen reader might not announce the page's text correctly. [Learn more](https://dequeuniversity.com/rules/axe/2.2/html-lang?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"html-lang-valid":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"html-lang-valid","description":"`\u003chtml>` element has a valid value for its `[lang]` attribute","helpText":"Specifying a valid [BCP 47 language](https://www.w3.org/International/questions/qa-choosing-language-tags#question) helps screen readers announce text properly. [Learn more](https://dequeuniversity.com/rules/axe/2.2/valid-lang?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"image-alt":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"image-alt","description":"Image elements have `[alt]` attributes","helpText":"Informative elements should aim for short, descriptive alternate text. Decorative elements can be ignored with an empty alt attribute.[Learn more](https://dequeuniversity.com/rules/axe/2.2/image-alt?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"input-image-alt":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"input-image-alt","description":"`\u003cinput type=\"image\">` elements do not have `[alt]` text","helpText":"When an image is being used as an `\u003cinput>` button, providing alternative text can help screen reader users understand the purpose of the button. [Learn more](https://dequeuniversity.com/rules/axe/2.2/input-image-alt?application=lighthouse)."},"label":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"label","description":"Form elements have associated labels","helpText":"Labels ensure that form controls are announced properly by assistive technologies, like screen readers. [Learn more](https://dequeuniversity.com/rules/axe/2.2/label?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"layout-table":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"layout-table","description":"Presentational `\u003ctable>` elements do not avoid using `\u003cth>`, `\u003ccaption>` or the `[summary]` attribute.","helpText":"A table being used for layout purposes should not include data elements, such as the th or caption elements or the summary attribute, because this can create a confusing experience for screen reader users. [Learn more](https://dequeuniversity.com/rules/axe/2.2/layout-table?application=lighthouse)."},"link-name":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"link-name","description":"Links do not have a discernible name","helpText":"Link text (and alternate text for images, when used as links) that is discernible, unique, and focusable improves the navigation experience for screen reader users. [Learn more](https://dequeuniversity.com/rules/axe/2.2/link-name?application=lighthouse)."},"list":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"list","description":"Lists do not contain only `\u003cli>` elements and script supporting elements (`\u003cscript>` and `\u003ctemplate>`).","helpText":"Screen readers have a specific way of announcing lists. Ensuring proper list structure aids screen reader output. [Learn more](https://dequeuniversity.com/rules/axe/2.2/list?application=lighthouse)."},"listitem":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"listitem","description":"List items (`\u003cli>`) are not contained within `\u003cul>` or `\u003col>` parent elements.","helpText":"Screen readers require list items (`\u003cli>`) to be contained within a parent `\u003cul>` or `\u003col>` to be announced properly. [Learn more](https://dequeuniversity.com/rules/axe/2.2/listitem?application=lighthouse)."},"meta-refresh":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"meta-refresh","description":"The document uses `\u003cmeta http-equiv=\"refresh\">`","helpText":"Users do not expect a page to refresh automatically, and doing so will move focus back to the top of the page. This may create a frustrating or confusing experience. [Learn more](https://dequeuniversity.com/rules/axe/2.2/meta-refresh?application=lighthouse)."},"meta-viewport":{"score":false,"displayValue":"","rawValue":false,"extendedInfo":{"value":{"description":"Ensures \u003cmeta name=\"viewport\"> does not disable text scaling and zooming","help":"Zooming and scaling must not be disabled","helpUrl":"https://dequeuniversity.com/rules/axe/3.0/meta-viewport?application=axeAPI","id":"meta-viewport","impact":"critical","nodes":[{"failureSummary":"Fix any of the following:\n  \u003cmeta> tag disables zooming on mobile devices","html":"\u003cmeta name=\"viewport\" content=\"width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0\">","impact":"critical","path":"1,HTML,0,HEAD,1,META","snippet":"\u003cmeta name=\"viewport\" content=\"width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0\">","target":["meta[name=\"viewport\"]"]}],"tags":["cat.sensory-and-visual-cues","wcag2aa","wcag144"]}},"scoringMode":"binary","name":"meta-viewport","description":"`[user-scalable=\"no\"]` is used in the `\u003cmeta name=\"viewport\">` element or the `[maximum-scale]` attribute is less than 5.","helpText":"Disabling zooming is problematic for users with low vision who rely on screen magnification to properly see the contents of a web page. [Learn more](https://dequeuniversity.com/rules/axe/2.2/meta-viewport?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[{"type":"node","selector":"meta[name=\"viewport\"]","path":"1,HTML,0,HEAD,1,META","snippet":"\u003cmeta name=\"viewport\" content=\"width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0\">"}]}},"object-alt":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"object-alt","description":"`\u003cobject>` elements do not have `[alt]` text","helpText":"Screen readers cannot translate non-text content. Adding alt text to `\u003cobject>` elements helps screen readers convey meaning to users. [Learn more](https://dequeuniversity.com/rules/axe/2.2/object-alt?application=lighthouse)."},"tabindex":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"tabindex","description":"No element has a `[tabindex]` value greater than 0","helpText":"A value greater than 0 implies an explicit navigation ordering. Although technically valid, this often creates frustrating experiences for users who rely on assistive technologies. [Learn more](https://dequeuniversity.com/rules/axe/2.2/tabindex?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"td-headers-attr":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"td-headers-attr","description":"Cells in a `\u003ctable>` element that use the `[headers]` attribute refers to other cells of that same table.","helpText":"Screen readers have features to make navigating tables easier. Ensuring `\u003ctd>` cells using the `[headers]` attribute only refer to other cells in the same table may improve the experience for screen reader users. [Learn more](https://dequeuniversity.com/rules/axe/2.2/td-headers-attr?application=lighthouse)."},"th-has-data-cells":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"th-has-data-cells","description":"`\u003cth>` elements and elements with `[role=\"columnheader\"/\"rowheader\"]` do not have data cells they describe.","helpText":"Screen readers have features to make navigating tables easier. Ensuring table headers always refer to some set of cells may improve the experience for screen reader users. [Learn more](https://dequeuniversity.com/rules/axe/2.2/th-has-data-cells?application=lighthouse)."},"valid-lang":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"valid-lang","description":"`[lang]` attributes do not have a valid value","helpText":"Specifying a valid [BCP 47 language](https://www.w3.org/International/questions/qa-choosing-language-tags#question) on elements helps ensure that text is pronounced correctly by a screen reader. [Learn more](https://dequeuniversity.com/rules/axe/2.2/valid-lang?application=lighthouse)."},"video-caption":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"video-caption","description":"`\u003cvideo>` elements contain a `\u003ctrack>` element with `[kind=\"captions\"]`","helpText":"When a video provides a caption it is easier for deaf and hearing impaired users to access its information. [Learn more](https://dequeuniversity.com/rules/axe/2.2/video-caption?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"video-description":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"video-description","description":"`\u003cvideo>` elements contain a `\u003ctrack>` element with `[kind=\"description\"]`","helpText":"Audio descriptions provide relevant information for videos that dialogue cannot, such as facial expressions and scenes. [Learn more](https://dequeuniversity.com/rules/axe/2.2/video-description?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"custom-controls-labels":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"custom-controls-labels","description":"Custom controls have associated labels","helpText":"Custom interactive controls have associated labels, provided by aria-label or aria-labelledby. [Learn more](https://developers.google.com/web/fundamentals/accessibility/how-to-review#try_it_with_a_screen_reader)."},"custom-controls-roles":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"custom-controls-roles","description":"Custom controls have ARIA roles","helpText":"Custom interactive controls have appropriate ARIA roles. [Learn more](https://developers.google.com/web/fundamentals/accessibility/how-to-review#try_it_with_a_screen_reader)."},"focus-traps":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"focus-traps","description":"User focus is not accidentally trapped in a region","helpText":"A user can tab into and out of any control or region without accidentally trapping their focus. [Learn more](https://developers.google.com/web/fundamentals/accessibility/how-to-review#start_with_the_keyboard)."},"focusable-controls":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"focusable-controls","description":"Interactive controls are keyboard focusable","helpText":"Custom interactive controls are keyboard focusable and display a focus indicator. [Learn more](https://developers.google.com/web/fundamentals/accessibility/how-to-review#start_with_the_keyboard)."},"heading-levels":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"heading-levels","description":"Headings don't skip levels","helpText":"Headings are used to create an outline for the page and heading levels are not skipped. [Learn more](https://developers.google.com/web/fundamentals/accessibility/how-to-review#take_advantage_of_headings_and_landmarks)."},"logical-tab-order":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"logical-tab-order","description":"The page has a logical tab order","helpText":"Tabbing through the page follows the visual layout. Users cannot focus elements that are offscreen. [Learn more](https://developers.google.com/web/fundamentals/accessibility/how-to-review#start_with_the_keyboard)."},"managed-focus":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"managed-focus","description":"The user's focus is directed to new content added to the page","helpText":"If new content, such as a dialog, is added to the page, the user's focus is directed to it. [Learn more](https://developers.google.com/web/fundamentals/accessibility/how-to-review#start_with_the_keyboard)."},"offscreen-content-hidden":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"offscreen-content-hidden","description":"Offscreen content is hidden from assistive technology","helpText":"Offscreen content is hidden with display: none or aria-hidden=true. [Learn more](https://developers.google.com/web/fundamentals/accessibility/how-to-review#try_it_with_a_screen_reader)."},"use-landmarks":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"use-landmarks","description":"HTML5 landmark elements are used to improve navigation","helpText":"Landmark elements (\u003cmain>, \u003cnav>, etc.) are used to improve the keyboard navigation of the page for assistive technology. [Learn more](https://developers.google.com/web/fundamentals/accessibility/how-to-review#take_advantage_of_headings_and_landmarks)."},"visual-order-follows-dom":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"visual-order-follows-dom","description":"Visual order on the page follows DOM order","helpText":"DOM order matches the visual order, improving navigation for assistive technology. [Learn more](https://developers.google.com/web/fundamentals/accessibility/how-to-review#try_it_with_a_screen_reader)."},"uses-long-cache-ttl":{"score":77,"displayValue":"12 assets found","rawValue":254380.39999999997,"extendedInfo":{"value":{"results":[{"url":"https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png","cacheControl":{"max-age":3600},"cacheLifetimeInSeconds":3600,"cacheLifetimeDisplay":"1 h","cacheHitProbability":0.2,"totalKb":"285 KB","totalBytes":292040,"wastedBytes":233632},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/material.min.js","cacheControl":{"max-age":3600},"cacheLifetimeInSeconds":3600,"cacheLifetimeDisplay":"1 h","cacheHitProbability":0.2,"totalKb":"12 KB","totalBytes":11790,"wastedBytes":9432},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/fetch.js","cacheControl":{"max-age":3600},"cacheLifetimeInSeconds":3600,"cacheLifetimeDisplay":"1 h","cacheHitProbability":0.2,"totalKb":"3 KB","totalBytes":3426,"wastedBytes":2740.8},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/feed.js","cacheControl":{"max-age":3600},"cacheLifetimeInSeconds":3600,"cacheLifetimeDisplay":"1 h","cacheHitProbability":0.2,"totalKb":"3 KB","totalBytes":2933,"wastedBytes":2346.4},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/promise.js","cacheControl":{"max-age":3600},"cacheLifetimeInSeconds":3600,"cacheLifetimeDisplay":"1 h","cacheHitProbability":0.2,"totalKb":"2 KB","totalBytes":2448,"wastedBytes":1958.4},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/idb.js","cacheControl":{"max-age":3600},"cacheLifetimeInSeconds":3600,"cacheLifetimeDisplay":"1 h","cacheHitProbability":0.2,"totalKb":"2 KB","totalBytes":1858,"wastedBytes":1486.4},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/app.js","cacheControl":{"max-age":3600},"cacheLifetimeInSeconds":3600,"cacheLifetimeDisplay":"1 h","cacheHitProbability":0.2,"totalKb":"1 KB","totalBytes":1323,"wastedBytes":1058.4},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/utility.js","cacheControl":{"max-age":3600},"cacheLifetimeInSeconds":3600,"cacheLifetimeDisplay":"1 h","cacheHitProbability":0.2,"totalKb":"1 KB","totalBytes":785,"wastedBytes":628},{"url":"https://facebookfeed-neel.firebaseapp.com/src/css/feed.css","cacheControl":{"max-age":3600},"cacheLifetimeInSeconds":3600,"cacheLifetimeDisplay":"1 h","cacheHitProbability":0.2,"totalKb":"1 KB","totalBytes":639,"wastedBytes":511.20000000000005},{"url":"https://facebookfeed-neel.firebaseapp.com/src/css/app.css","cacheControl":{"max-age":3600},"cacheLifetimeInSeconds":3600,"cacheLifetimeDisplay":"1 h","cacheHitProbability":0.2,"totalKb":"0 KB","totalBytes":207,"wastedBytes":165.60000000000002},{"url":"https://fonts.googleapis.com/css?family=Roboto:400,700","cacheControl":{"private":true,"max-age":86400,"stale-while-revalidate":"604800"},"cacheLifetimeInSeconds":86400,"cacheLifetimeDisplay":"1 d","cacheHitProbability":0.6,"totalKb":"1 KB","totalBytes":681,"wastedBytes":272.40000000000003},{"url":"https://fonts.googleapis.com/icon?family=Material+Icons","cacheControl":{"private":true,"max-age":86400,"stale-while-revalidate":"604800"},"cacheLifetimeInSeconds":86400,"cacheLifetimeDisplay":"1 d","cacheHitProbability":0.6,"totalKb":"0 KB","totalBytes":372,"wastedBytes":148.8}],"queryStringCount":2}},"scoringMode":"numeric","name":"uses-long-cache-ttl","description":"Uses inefficient cache policy on static assets","helpText":"A long cache lifetime can speed up repeat visits to your page. [Learn more](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching#cache-control).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Cache TTL"},{"type":"text","itemType":"text","text":"Size (KB)"}],"items":[[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png"},{"type":"text","text":"1 h"},{"type":"text","text":"285 KB"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/material.min.js"},{"type":"text","text":"1 h"},{"type":"text","text":"12 KB"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/fetch.js"},{"type":"text","text":"1 h"},{"type":"text","text":"3 KB"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/feed.js"},{"type":"text","text":"1 h"},{"type":"text","text":"3 KB"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/promise.js"},{"type":"text","text":"1 h"},{"type":"text","text":"2 KB"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/idb.js"},{"type":"text","text":"1 h"},{"type":"text","text":"2 KB"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/app.js"},{"type":"text","text":"1 h"},{"type":"text","text":"1 KB"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/utility.js"},{"type":"text","text":"1 h"},{"type":"text","text":"1 KB"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/css/feed.css"},{"type":"text","text":"1 h"},{"type":"text","text":"1 KB"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/css/app.css"},{"type":"text","text":"1 h"},{"type":"text","text":"0 KB"}],[{"type":"url","text":"https://fonts.googleapis.com/css?family=Roboto:400,700"},{"type":"text","text":"1 d"},{"type":"text","text":"1 KB"}],[{"type":"url","text":"https://fonts.googleapis.com/icon?family=Material+Icons"},{"type":"text","text":"1 d"},{"type":"text","text":"0 KB"}]]}},"total-byte-weight":{"score":100,"displayValue":"Total size was 404 KB","rawValue":413236,"extendedInfo":{"value":{"results":[{"url":"https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png","totalBytes":292040,"totalKb":"285 KB","totalMs":"1,670 ms"},{"url":"https://fonts.gstatic.com/s/materialicons/v36/flUhRq6tzZclQEJ-Vdg-IuiaDsNcIhQ8tQ.woff2","totalBytes":49172,"totalKb":"48 KB","totalMs":"280 ms"},{"url":"https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css","totalBytes":18885,"totalKb":"18 KB","totalMs":"110 ms"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/material.min.js","totalBytes":11790,"totalKb":"12 KB","totalMs":"70 ms"},{"url":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu4mxKKTU1Kg.woff2","totalBytes":10814,"totalKb":"11 KB","totalMs":"60 ms"},{"url":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu7GxKKTU1Kvnz.woff2","totalBytes":8118,"totalKb":"8 KB","totalMs":"50 ms"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/fetch.js","totalBytes":3426,"totalKb":"3 KB","totalMs":"20 ms"},{"url":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu7WxKKTU1Kvnz.woff2","totalBytes":3375,"totalKb":"3 KB","totalMs":"20 ms"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/feed.js","totalBytes":2933,"totalKb":"3 KB","totalMs":"20 ms"},{"url":"https://facebookfeed-neel.firebaseio.com/posts.json","totalBytes":2515,"totalKb":"2 KB","totalMs":"10 ms"}],"totalCompletedRequests":27}},"scoringMode":"numeric","name":"total-byte-weight","description":"Avoids enormous network payloads","helpText":"Large network payloads cost users real money and are highly correlated with long load times. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/network-payloads).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Total Size"},{"type":"text","itemType":"text","text":"Transfer Time"}],"items":[[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png"},{"type":"text","text":"285 KB"},{"type":"text","text":"1,670 ms"}],[{"type":"url","text":"https://fonts.gstatic.com/s/materialicons/v36/flUhRq6tzZclQEJ-Vdg-IuiaDsNcIhQ8tQ.woff2"},{"type":"text","text":"48 KB"},{"type":"text","text":"280 ms"}],[{"type":"url","text":"https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css"},{"type":"text","text":"18 KB"},{"type":"text","text":"110 ms"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/material.min.js"},{"type":"text","text":"12 KB"},{"type":"text","text":"70 ms"}],[{"type":"url","text":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu4mxKKTU1Kg.woff2"},{"type":"text","text":"11 KB"},{"type":"text","text":"60 ms"}],[{"type":"url","text":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu7GxKKTU1Kvnz.woff2"},{"type":"text","text":"8 KB"},{"type":"text","text":"50 ms"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/fetch.js"},{"type":"text","text":"3 KB"},{"type":"text","text":"20 ms"}],[{"type":"url","text":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu7WxKKTU1Kvnz.woff2"},{"type":"text","text":"3 KB"},{"type":"text","text":"20 ms"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/feed.js"},{"type":"text","text":"3 KB"},{"type":"text","text":"20 ms"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseio.com/posts.json"},{"type":"text","text":"2 KB"},{"type":"text","text":"10 ms"}]]}},"offscreen-images":{"score":0,"displayValue":"Potential savings of 545 KB (~3,200 ms)","rawValue":3200,"extendedInfo":{"value":{"wastedMs":3200,"wastedKb":545,"results":[{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c","preview":{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c","mimeType":"image/png"},"requestStartTime":1486182.238294,"totalBytes":157759,"wastedBytes":157759,"wastedPercent":100,"wastedKb":"154 KB","wastedMs":"900 ms","totalKb":"154 KB","totalMs":"900 ms","potentialSavings":"154 KB (100%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0","preview":{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0","mimeType":"image/png"},"requestStartTime":1486182.244326,"totalBytes":154974,"wastedBytes":154974,"wastedPercent":100,"wastedKb":"151 KB","wastedMs":"890 ms","totalKb":"151 KB","totalMs":"890 ms","potentialSavings":"151 KB (100%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&token=60c2ac2a-de60-4ebc-b970-70264d96a80b","preview":{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&token=60c2ac2a-de60-4ebc-b970-70264d96a80b","mimeType":"image/png"},"requestStartTime":1486182.240525,"totalBytes":136551,"wastedBytes":136551,"wastedPercent":100,"wastedKb":"133 KB","wastedMs":"780 ms","totalKb":"133 KB","totalMs":"780 ms","potentialSavings":"133 KB (100%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&token=d0181e98-3ea9-499b-865e-8cec92fa1e33","preview":{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&token=d0181e98-3ea9-499b-865e-8cec92fa1e33","mimeType":"image/png"},"requestStartTime":1486182.248715,"totalBytes":108988,"wastedBytes":108988,"wastedPercent":100,"wastedKb":"106 KB","wastedMs":"620 ms","totalKb":"106 KB","totalMs":"620 ms","potentialSavings":"106 KB (100%)"}]}},"scoringMode":"binary","informative":true,"name":"offscreen-images","description":"Offscreen images","helpText":"Consider lazy-loading offscreen and hidden images to improve page load speed and time to interactive. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/offscreen-images).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"thumbnail","text":""},{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Original"},{"type":"text","itemType":"text","text":"Potential Savings"}],"items":[[{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c","mimeType":"image/png"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c"},{"type":"text","text":"154 KB"},{"type":"text","text":"154 KB (100%)"}],[{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0","mimeType":"image/png"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0"},{"type":"text","text":"151 KB"},{"type":"text","text":"151 KB (100%)"}],[{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&token=60c2ac2a-de60-4ebc-b970-70264d96a80b","mimeType":"image/png"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&token=60c2ac2a-de60-4ebc-b970-70264d96a80b"},{"type":"text","text":"133 KB"},{"type":"text","text":"133 KB (100%)"}],[{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&token=d0181e98-3ea9-499b-865e-8cec92fa1e33","mimeType":"image/png"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&token=d0181e98-3ea9-499b-865e-8cec92fa1e33"},{"type":"text","text":"106 KB"},{"type":"text","text":"106 KB (100%)"}]]}},"unminified-css":{"score":100,"displayValue":"","rawValue":0,"extendedInfo":{"value":{"wastedMs":0,"wastedKb":0,"results":[]}},"scoringMode":"binary","informative":true,"name":"unminified-css","description":"Minify CSS","helpText":"Minifying CSS files can reduce network payload sizes. [Learn more](https://developers.google.com/speed/docs/insights/MinifyResources).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Original"},{"type":"text","itemType":"text","text":"Potential Savings"}],"items":[]}},"unminified-javascript":{"score":100,"displayValue":"","rawValue":0,"extendedInfo":{"value":{"wastedMs":0,"wastedKb":0,"results":[]}},"scoringMode":"binary","informative":true,"name":"unminified-javascript","description":"Minify JavaScript","helpText":"Minifying JavaScript files can reduce payload sizes and script parse time. [Learn more](https://developers.google.com/speed/docs/insights/MinifyResources).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Original"},{"type":"text","itemType":"text","text":"Potential Savings"}],"items":[]}},"unused-css-rules":{"score":90,"displayValue":"Potential savings of 17 KB (~100 ms)","rawValue":100,"extendedInfo":{"value":{"wastedMs":100,"wastedKb":17,"results":[{"url":"https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css","wastedBytes":17300,"wastedPercent":91.60692168866555,"totalBytes":18885,"wastedKb":"17 KB","wastedMs":"100 ms","totalKb":"18 KB","totalMs":"110 ms","potentialSavings":"17 KB (92%)"}]}},"scoringMode":"binary","informative":true,"name":"unused-css-rules","description":"Unused CSS rules","helpText":"Remove unused rules from stylesheets to reduce unnecessary bytes consumed by network activity. [Learn more](https://developers.google.com/speed/docs/insights/OptimizeCSSDelivery)","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Original"},{"type":"text","itemType":"text","text":"Potential Savings"}],"items":[[{"type":"url","text":"https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css"},{"type":"text","text":"18 KB"},{"type":"text","text":"17 KB (92%)"}]]}},"uses-webp-images":{"score":0,"displayValue":"Potential savings of 463 KB (~2,720 ms)","rawValue":2720,"extendedInfo":{"value":{"wastedMs":2720,"wastedKb":463,"results":[{"url":"https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png","fromProtocol":true,"isCrossOrigin":false,"preview":{"url":"https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png","mimeType":"image/png","type":"thumbnail"},"totalBytes":291744,"wastedBytes":233594,"wastedKb":"228 KB","wastedMs":"1,340 ms","totalKb":"285 KB","totalMs":"1,670 ms","potentialSavings":"228 KB (80%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A32%3A53.884Z.png?alt=media&token=aca0478e-23b6-45d9-90d7-594641c37b77","fromProtocol":true,"isCrossOrigin":true,"preview":{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A32%3A53.884Z.png?alt=media&token=aca0478e-23b6-45d9-90d7-594641c37b77","mimeType":"image/png","type":"thumbnail"},"totalBytes":215495,"wastedBytes":45509,"wastedKb":"44 KB","wastedMs":"260 ms","totalKb":"210 KB","totalMs":"1,230 ms","potentialSavings":"44 KB (21%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A42%3A19.478Z.png?alt=media&token=99f7a653-5780-411b-91c6-ca1a86b4a8a5","fromProtocol":true,"isCrossOrigin":true,"preview":{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A42%3A19.478Z.png?alt=media&token=99f7a653-5780-411b-91c6-ca1a86b4a8a5","mimeType":"image/png","type":"thumbnail"},"totalBytes":145182,"wastedBytes":33278,"wastedKb":"32 KB","wastedMs":"190 ms","totalKb":"142 KB","totalMs":"830 ms","potentialSavings":"32 KB (23%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&token=60c2ac2a-de60-4ebc-b970-70264d96a80b","fromProtocol":true,"isCrossOrigin":true,"preview":{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&token=60c2ac2a-de60-4ebc-b970-70264d96a80b","mimeType":"image/png","type":"thumbnail"},"totalBytes":136551,"wastedBytes":33257,"wastedKb":"32 KB","wastedMs":"190 ms","totalKb":"133 KB","totalMs":"780 ms","potentialSavings":"32 KB (24%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0","fromProtocol":true,"isCrossOrigin":true,"preview":{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0","mimeType":"image/png","type":"thumbnail"},"totalBytes":154974,"wastedBytes":33030,"wastedKb":"32 KB","wastedMs":"190 ms","totalKb":"151 KB","totalMs":"890 ms","potentialSavings":"32 KB (21%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&token=d0181e98-3ea9-499b-865e-8cec92fa1e33","fromProtocol":true,"isCrossOrigin":true,"preview":{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&token=d0181e98-3ea9-499b-865e-8cec92fa1e33","mimeType":"image/png","type":"thumbnail"},"totalBytes":108988,"wastedBytes":32258,"wastedKb":"32 KB","wastedMs":"180 ms","totalKb":"106 KB","totalMs":"620 ms","potentialSavings":"32 KB (30%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A41%3A06.899Z.png?alt=media&token=ab32239e-a34f-4a94-880a-bc03dec7121b","fromProtocol":true,"isCrossOrigin":true,"preview":{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A41%3A06.899Z.png?alt=media&token=ab32239e-a34f-4a94-880a-bc03dec7121b","mimeType":"image/png","type":"thumbnail"},"totalBytes":138792,"wastedBytes":32098,"wastedKb":"31 KB","wastedMs":"180 ms","totalKb":"136 KB","totalMs":"790 ms","potentialSavings":"31 KB (23%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c","fromProtocol":true,"isCrossOrigin":true,"preview":{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c","mimeType":"image/png","type":"thumbnail"},"totalBytes":157759,"wastedBytes":31403,"wastedKb":"31 KB","wastedMs":"180 ms","totalKb":"154 KB","totalMs":"900 ms","potentialSavings":"31 KB (20%)"}]}},"scoringMode":"binary","informative":true,"name":"uses-webp-images","description":"Serve images in next-gen formats","helpText":"Image formats like JPEG 2000, JPEG XR, and WebP often provide better compression than PNG or JPEG, which means faster downloads and less data consumption. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/webp).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"thumbnail","text":""},{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Original"},{"type":"text","itemType":"text","text":"Potential Savings"}],"items":[[{"url":"https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png","mimeType":"image/png","type":"thumbnail"},{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png"},{"type":"text","text":"285 KB"},{"type":"text","text":"228 KB (80%)"}],[{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A32%3A53.884Z.png?alt=media&token=aca0478e-23b6-45d9-90d7-594641c37b77","mimeType":"image/png","type":"thumbnail"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A32%3A53.884Z.png?alt=media&token=aca0478e-23b6-45d9-90d7-594641c37b77"},{"type":"text","text":"210 KB"},{"type":"text","text":"44 KB (21%)"}],[{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A42%3A19.478Z.png?alt=media&token=99f7a653-5780-411b-91c6-ca1a86b4a8a5","mimeType":"image/png","type":"thumbnail"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A42%3A19.478Z.png?alt=media&token=99f7a653-5780-411b-91c6-ca1a86b4a8a5"},{"type":"text","text":"142 KB"},{"type":"text","text":"32 KB (23%)"}],[{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&token=60c2ac2a-de60-4ebc-b970-70264d96a80b","mimeType":"image/png","type":"thumbnail"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&token=60c2ac2a-de60-4ebc-b970-70264d96a80b"},{"type":"text","text":"133 KB"},{"type":"text","text":"32 KB (24%)"}],[{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0","mimeType":"image/png","type":"thumbnail"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0"},{"type":"text","text":"151 KB"},{"type":"text","text":"32 KB (21%)"}],[{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&token=d0181e98-3ea9-499b-865e-8cec92fa1e33","mimeType":"image/png","type":"thumbnail"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&token=d0181e98-3ea9-499b-865e-8cec92fa1e33"},{"type":"text","text":"106 KB"},{"type":"text","text":"32 KB (30%)"}],[{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A41%3A06.899Z.png?alt=media&token=ab32239e-a34f-4a94-880a-bc03dec7121b","mimeType":"image/png","type":"thumbnail"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A41%3A06.899Z.png?alt=media&token=ab32239e-a34f-4a94-880a-bc03dec7121b"},{"type":"text","text":"136 KB"},{"type":"text","text":"31 KB (23%)"}],[{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c","mimeType":"image/png","type":"thumbnail"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c"},{"type":"text","text":"154 KB"},{"type":"text","text":"31 KB (20%)"}]]}},"uses-optimized-images":{"score":100,"displayValue":"","rawValue":0,"extendedInfo":{"value":{"wastedMs":0,"wastedKb":0,"results":[]}},"scoringMode":"binary","informative":true,"name":"uses-optimized-images","description":"Optimize images","helpText":"Optimized images load faster and consume less cellular data. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/optimize-images).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"thumbnail","text":""},{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Original"},{"type":"text","itemType":"text","text":"Potential Savings"}],"items":[]}},"uses-request-compression":{"score":90,"displayValue":"Potential savings of 1 KB (~10 ms)","rawValue":10,"extendedInfo":{"value":{"wastedMs":10,"wastedKb":1,"results":[{"url":"https://facebookfeed-neel.firebaseio.com/posts.json","totalBytes":2181,"wastedBytes":1438,"wastedKb":"1 KB","wastedMs":"10 ms","totalKb":"2 KB","totalMs":"10 ms","potentialSavings":"1 KB (66%)"}]}},"scoringMode":"binary","informative":true,"name":"uses-request-compression","description":"Enable text compression","helpText":"Text-based responses should be served with compression (gzip, deflate or brotli) to minimize total network bytes. [Learn more](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/optimize-encoding-and-transfer).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"Uncompressed resource URL"},{"type":"text","itemType":"text","text":"Original"},{"type":"text","itemType":"text","text":"GZIP Savings"}],"items":[[{"type":"url","text":"https://facebookfeed-neel.firebaseio.com/posts.json"},{"type":"text","text":"2 KB"},{"type":"text","text":"1 KB (66%)"}]]}},"uses-responsive-images":{"score":0,"displayValue":"Potential savings of 489 KB (~2,870 ms)","rawValue":2870,"extendedInfo":{"value":{"wastedMs":2870,"wastedKb":489,"results":[{"url":"https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png","preview":{"type":"thumbnail","url":"https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png","mimeType":"image/png"},"totalBytes":291744,"wastedBytes":206363,"wastedPercent":70.73412511223414,"isWasteful":true,"wastedKb":"202 KB","wastedMs":"1,180 ms","totalKb":"285 KB","totalMs":"1,670 ms","potentialSavings":"202 KB (71%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A32%3A53.884Z.png?alt=media&token=aca0478e-23b6-45d9-90d7-594641c37b77","preview":{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A32%3A53.884Z.png?alt=media&token=aca0478e-23b6-45d9-90d7-594641c37b77","mimeType":"image/png"},"totalBytes":215495,"wastedBytes":60027,"wastedPercent":27.85544318857823,"isWasteful":true,"wastedKb":"59 KB","wastedMs":"340 ms","totalKb":"210 KB","totalMs":"1,230 ms","potentialSavings":"59 KB (28%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c","preview":{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c","mimeType":"image/png"},"totalBytes":157759,"wastedBytes":43944,"wastedPercent":27.85544318857823,"isWasteful":true,"wastedKb":"43 KB","wastedMs":"250 ms","totalKb":"154 KB","totalMs":"900 ms","potentialSavings":"43 KB (28%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0","preview":{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0","mimeType":"image/png"},"totalBytes":154974,"wastedBytes":43169,"wastedPercent":27.85544318857823,"isWasteful":true,"wastedKb":"42 KB","wastedMs":"250 ms","totalKb":"151 KB","totalMs":"890 ms","potentialSavings":"42 KB (28%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A42%3A19.478Z.png?alt=media&token=99f7a653-5780-411b-91c6-ca1a86b4a8a5","preview":{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A42%3A19.478Z.png?alt=media&token=99f7a653-5780-411b-91c6-ca1a86b4a8a5","mimeType":"image/png"},"totalBytes":145182,"wastedBytes":40441,"wastedPercent":27.85544318857823,"isWasteful":true,"wastedKb":"39 KB","wastedMs":"230 ms","totalKb":"142 KB","totalMs":"830 ms","potentialSavings":"39 KB (28%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A41%3A06.899Z.png?alt=media&token=ab32239e-a34f-4a94-880a-bc03dec7121b","preview":{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A41%3A06.899Z.png?alt=media&token=ab32239e-a34f-4a94-880a-bc03dec7121b","mimeType":"image/png"},"totalBytes":138792,"wastedBytes":38661,"wastedPercent":27.85544318857823,"isWasteful":true,"wastedKb":"38 KB","wastedMs":"220 ms","totalKb":"136 KB","totalMs":"790 ms","potentialSavings":"38 KB (28%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&token=60c2ac2a-de60-4ebc-b970-70264d96a80b","preview":{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&token=60c2ac2a-de60-4ebc-b970-70264d96a80b","mimeType":"image/png"},"totalBytes":136551,"wastedBytes":38037,"wastedPercent":27.85544318857823,"isWasteful":true,"wastedKb":"37 KB","wastedMs":"220 ms","totalKb":"133 KB","totalMs":"780 ms","potentialSavings":"37 KB (28%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&token=d0181e98-3ea9-499b-865e-8cec92fa1e33","preview":{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&token=d0181e98-3ea9-499b-865e-8cec92fa1e33","mimeType":"image/png"},"totalBytes":108988,"wastedBytes":30359,"wastedPercent":27.85544318857823,"isWasteful":true,"wastedKb":"30 KB","wastedMs":"170 ms","totalKb":"106 KB","totalMs":"620 ms","potentialSavings":"30 KB (28%)"}]}},"scoringMode":"binary","informative":true,"name":"uses-responsive-images","description":"Properly size images","helpText":"Serve images that are appropriately-sized to save cellular data and improve load time. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/oversized-images).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"thumbnail","text":""},{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Original"},{"type":"text","itemType":"text","text":"Potential Savings"}],"items":[[{"type":"thumbnail","url":"https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png","mimeType":"image/png"},{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png"},{"type":"text","text":"285 KB"},{"type":"text","text":"202 KB (71%)"}],[{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A32%3A53.884Z.png?alt=media&token=aca0478e-23b6-45d9-90d7-594641c37b77","mimeType":"image/png"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A32%3A53.884Z.png?alt=media&token=aca0478e-23b6-45d9-90d7-594641c37b77"},{"type":"text","text":"210 KB"},{"type":"text","text":"59 KB (28%)"}],[{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c","mimeType":"image/png"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c"},{"type":"text","text":"154 KB"},{"type":"text","text":"43 KB (28%)"}],[{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0","mimeType":"image/png"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0"},{"type":"text","text":"151 KB"},{"type":"text","text":"42 KB (28%)"}],[{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A42%3A19.478Z.png?alt=media&token=99f7a653-5780-411b-91c6-ca1a86b4a8a5","mimeType":"image/png"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A42%3A19.478Z.png?alt=media&token=99f7a653-5780-411b-91c6-ca1a86b4a8a5"},{"type":"text","text":"142 KB"},{"type":"text","text":"39 KB (28%)"}],[{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A41%3A06.899Z.png?alt=media&token=ab32239e-a34f-4a94-880a-bc03dec7121b","mimeType":"image/png"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A41%3A06.899Z.png?alt=media&token=ab32239e-a34f-4a94-880a-bc03dec7121b"},{"type":"text","text":"136 KB"},{"type":"text","text":"38 KB (28%)"}],[{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&token=60c2ac2a-de60-4ebc-b970-70264d96a80b","mimeType":"image/png"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&token=60c2ac2a-de60-4ebc-b970-70264d96a80b"},{"type":"text","text":"133 KB"},{"type":"text","text":"37 KB (28%)"}],[{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&token=d0181e98-3ea9-499b-865e-8cec92fa1e33","mimeType":"image/png"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&token=d0181e98-3ea9-499b-865e-8cec92fa1e33"},{"type":"text","text":"106 KB"},{"type":"text","text":"30 KB (28%)"}]]}},"appcache-manifest":{"score":true,"displayValue":"","rawValue":true,"debugString":"","scoringMode":"binary","name":"appcache-manifest","description":"Avoids Application Cache","helpText":"Application Cache is deprecated. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/appcache)."},"dom-size":{"score":100,"displayValue":"207 nodes","rawValue":207,"extendedInfo":{"value":[{"title":"Total DOM Nodes","value":"207","target":"\u003c 1,500 nodes"},{"title":"DOM Depth","value":"13","snippet":"html.mdl-js >\n  body >\n    div#app >\n      div.mdl-layout__container >\n        div.mdl-layout.mdl-js-layout.mdl-layout--fixed-header.has-drawer.is-small-screen.is-upgraded >\n          main.mdl-layout__content.mat-typography >\n            div#create-post >\n              form >\n                div.input-section >\n                  div#location-loader.mdl-spinner.mdl-js-spinner.is-active.is-upgraded >\n                    div.mdl-spinner__layer.mdl-spinner__layer-1 >\n                      div.mdl-spinner__circle-clipper.mdl-spinner__left >\n                        div.mdl-spinner__circle","target":"\u003c 32"},{"title":"Maximum Children","value":"25","snippet":"Element with most children:\nhead","target":"\u003c 60 nodes"}]},"scoringMode":"numeric","name":"dom-size","description":"Avoids an excessive DOM size","helpText":"Browser engineers recommend pages contain fewer than ~1,500 DOM nodes. The sweet spot is a tree depth \u003c 32 elements and fewer than 60 children/parent element. A large DOM can increase memory usage, cause longer [style calculations](https://developers.google.com/web/fundamentals/performance/rendering/reduce-the-scope-and-complexity-of-style-calculations), and produce costly [layout reflows](https://developers.google.com/speed/articles/reflow). [Learn more](https://developers.google.com/web/fundamentals/performance/rendering/).","details":{"type":"cards","header":{"type":"text","text":"View details"},"items":[{"title":"Total DOM Nodes","value":"207","target":"\u003c 1,500 nodes"},{"title":"DOM Depth","value":"13","snippet":"html.mdl-js >\n  body >\n    div#app >\n      div.mdl-layout__container >\n        div.mdl-layout.mdl-js-layout.mdl-layout--fixed-header.has-drawer.is-small-screen.is-upgraded >\n          main.mdl-layout__content.mat-typography >\n            div#create-post >\n              form >\n                div.input-section >\n                  div#location-loader.mdl-spinner.mdl-js-spinner.is-active.is-upgraded >\n                    div.mdl-spinner__layer.mdl-spinner__layer-1 >\n                      div.mdl-spinner__circle-clipper.mdl-spinner__left >\n                        div.mdl-spinner__circle","target":"\u003c 32"},{"title":"Maximum Children","value":"25","snippet":"Element with most children:\nhead","target":"\u003c 60 nodes"}]}},"external-anchors-use-rel-noopener":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"value":[]},"scoringMode":"binary","name":"external-anchors-use-rel-noopener","description":"Opens external anchors using `rel=\"noopener\"`","helpText":"Open new tabs using `rel=\"noopener\"` to improve performance and prevent security vulnerabilities. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/noopener).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Target"},{"type":"text","itemType":"text","text":"Rel"}],"items":[]}},"geolocation-on-start":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"value":[]},"scoringMode":"binary","name":"geolocation-on-start","description":"Avoids requesting the geolocation permission on page load","helpText":"Users are mistrustful of or confused by sites that request their location without context. Consider tying the request to user gestures instead. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/geolocation-on-load).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Location"}],"items":[]}},"link-blocking-first-paint":{"score":0,"displayValue":"5 resources delayed first paint by 854 ms","rawValue":854,"extendedInfo":{"value":{"wastedMs":"854 ms","results":[{"url":"https://fonts.googleapis.com/css?family=Roboto:400,700","totalKb":"0.67 KB","totalMs":"832 ms"},{"url":"https://fonts.googleapis.com/icon?family=Material+Icons","totalKb":"0.36 KB","totalMs":"837 ms"},{"url":"https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css","totalKb":"18.44 KB","totalMs":"842 ms"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/css/app.css","totalKb":"0.2 KB","totalMs":"850 ms"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/css/feed.css","totalKb":"0.62 KB","totalMs":"854 ms"}]}},"scoringMode":"binary","informative":true,"name":"link-blocking-first-paint","description":"Reduce render-blocking stylesheets","helpText":"External stylesheets are blocking the first paint of your page. Consider delivering critical CSS via `\u003cstyle>` tags and deferring non-critical styles. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/blocking-resources).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Size (KB)"},{"type":"text","itemType":"text","text":"Delayed Paint By (ms)"}],"items":[[{"type":"url","text":"https://fonts.googleapis.com/css?family=Roboto:400,700"},{"type":"text","text":"0.67 KB"},{"type":"text","text":"832 ms"}],[{"type":"url","text":"https://fonts.googleapis.com/icon?family=Material+Icons"},{"type":"text","text":"0.36 KB"},{"type":"text","text":"837 ms"}],[{"type":"url","text":"https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css"},{"type":"text","text":"18.44 KB"},{"type":"text","text":"842 ms"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/css/app.css"},{"type":"text","text":"0.2 KB"},{"type":"text","text":"850 ms"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/css/feed.css"},{"type":"text","text":"0.62 KB"},{"type":"text","text":"854 ms"}]]}},"no-document-write":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"value":[]},"scoringMode":"binary","name":"no-document-write","description":"Avoids `document.write()`","helpText":"For users on slow connections, external scripts dynamically injected via `document.write()` can delay page load by tens of seconds. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/document-write).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Location"}],"items":[]}},"no-mutation-events":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"value":{"results":[]}},"scoringMode":"binary","name":"no-mutation-events","description":"Avoids Mutation Events in its own scripts","helpText":"Mutation Events are deprecated and harm performance. Consider using Mutation Observers instead. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/mutation-events).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"code","text":"Event"},{"type":"text","itemType":"text","text":"Line"},{"type":"text","itemType":"text","text":"Col"},{"type":"text","itemType":"code","text":"Snippet"}],"items":[]}},"no-vulnerable-libraries":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"jsLibs":[{"name":"Material Design Lite","npmPkgName":"material-design-lite","version":null,"vulns":[]}],"vulnerabilities":[]},"scoringMode":"binary","name":"no-vulnerable-libraries","description":"Avoids front-end JavaScript libraries with known security vulnerabilities","helpText":"Some third-party scripts may contain known security vulnerabilities  that are easily identified and exploited by attackers.","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"link","text":"Library Version"},{"type":"text","itemType":"text","text":"Vulnerability Count"},{"type":"text","itemType":"text","text":"Highest Severity"}],"items":[]}},"no-websql":{"score":true,"displayValue":"","rawValue":true,"debugString":"","scoringMode":"binary","name":"no-websql","description":"Avoids WebSQL DB","helpText":"Web SQL is deprecated. Consider using IndexedDB instead. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/web-sql)."},"notification-on-start":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"value":[]},"scoringMode":"binary","name":"notification-on-start","description":"Avoids requesting the notification permission on page load","helpText":"Users are mistrustful of or confused by sites that request to send notifications without context. Consider tying the request to user gestures instead. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/notifications-on-load).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Location"}],"items":[]}},"password-inputs-can-be-pasted-into":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"value":[]},"scoringMode":"binary","name":"password-inputs-can-be-pasted-into","description":"Allows users to paste into password fields","helpText":"Preventing password pasting undermines good security policy. [Learn more](https://www.ncsc.gov.uk/blog-post/let-them-paste-passwords)","details":{"type":"list","header":{"type":"text","text":"Password inputs that prevent pasting into"},"items":[]}},"script-blocking-first-paint":{"score":100,"displayValue":"","rawValue":0,"extendedInfo":{"value":{"wastedMs":"0 ms","results":[]}},"scoringMode":"binary","informative":true,"name":"script-blocking-first-paint","description":"Reduce render-blocking scripts","helpText":"Script elements are blocking the first paint of your page. Consider inlining critical scripts and deferring non-critical ones. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/blocking-resources).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Size (KB)"},{"type":"text","itemType":"text","text":"Delayed Paint By (ms)"}],"items":[]}},"uses-http2":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"value":{"results":[]}},"scoringMode":"binary","name":"uses-http2","description":"Uses HTTP/2 for its own resources","helpText":"HTTP/2 offers many benefits over HTTP/1.1, including binary headers, multiplexing, and server push. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/http2).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Protocol"}],"items":[]}},"uses-passive-event-listeners":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"value":[]},"scoringMode":"binary","name":"uses-passive-event-listeners","description":"Uses passive listeners to improve scrolling performance","helpText":"Consider marking your touch and wheel event listeners as `passive` to improve your page's scroll performance. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/passive-event-listeners).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Location"}],"items":[]}},"meta-description":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","name":"meta-description","description":"Document does not have a meta description","helpText":"Meta descriptions may be included in search results to concisely summarize page content. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/description)."},"http-status-code":{"score":true,"displayValue":"","rawValue":true,"scoringMode":"binary","name":"http-status-code","description":"Page has successful HTTP status code","helpText":"Pages with unsuccessful HTTP status codes may not be indexed properly. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/successful-http-code)."},"font-size":{"score":true,"displayValue":"","rawValue":true,"debugString":null,"scoringMode":"binary","name":"font-size","description":"Document uses legible font sizes","helpText":"Font sizes less than 12px are too small to be legible and require mobile visitors to “pinch to zoom” in order to read. Strive to have >60% of page text ≥12px. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/font-sizes).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"Source"},{"type":"text","itemType":"code","text":"Selector"},{"type":"text","itemType":"text","text":"% of Page Text"},{"type":"text","itemType":"text","text":"Font Size"}],"items":[[{"type":"url","text":"Legible text"},{"type":"code","text":null},{"type":"text","text":"100.00%"},{"type":"text","text":"≥ 12px"}]]}},"link-text":{"score":true,"displayValue":"","rawValue":true,"scoringMode":"binary","name":"link-text","description":"Links have descriptive text","helpText":"Descriptive link text helps search engines understand your content. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/descriptive-link-text).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"Link destination"},{"type":"text","itemType":"text","text":"Link Text"}],"items":[]}},"is-crawlable":{"score":true,"displayValue":"","rawValue":true,"scoringMode":"binary","name":"is-crawlable","description":"Page isn’t blocked from indexing","helpText":"Search engines are unable to include your pages in search results if they don't have permission to crawl them. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/indexing).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"code","text":"Blocking Directive Source"}],"items":[]}},"hreflang":{"score":true,"displayValue":"","rawValue":true,"scoringMode":"binary","name":"hreflang","description":"Document has a valid `hreflang`","helpText":"hreflang allows crawlers to discover alternate translations of the page content. [Learn more](https://support.google.com/webmasters/answer/189077).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"code","text":"Source"}],"items":[]}},"plugins":{"score":true,"displayValue":"","rawValue":true,"scoringMode":"binary","name":"plugins","description":"Document avoids plugins","helpText":"Most mobile devices do not support plugins, and many desktop browsers restrict them.","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"code","text":"Element source"}],"items":[]}},"canonical":{"score":true,"displayValue":"","rawValue":true,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"canonical","description":"Document has a valid `rel=canonical`","helpText":"Canonical links suggest which URL to show in search results. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/canonical)."},"mobile-friendly":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"mobile-friendly","description":"Page is mobile friendly","helpText":"Take the [Mobile-Friendly Test](https://search.google.com/test/mobile-friendly) to check for audits not covered by Lighthouse, like sizing tap targets appropriately. [Learn more](https://developers.google.com/search/mobile-sites/)."},"structured-data":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"structured-data","description":"Structured data is valid","helpText":"Run the [Structured Data Testing Tool](https://search.google.com/structured-data/testing-tool/) and the [Structured Data Linter](http://linter.structured-data.org/) to validate structured data. [Learn more](https://developers.google.com/search/docs/guides/mark-up-content)."}},"runtimeConfig":{"environment":[{"name":"Device Emulation","enabled":true,"description":"Nexus 5X"},{"name":"Network Throttling","enabled":true,"description":"562.5ms RTT, 1.4Mbps down, 0.7Mbps up"},{"name":"CPU Throttling","enabled":true,"description":"4x slowdown"}],"blockedUrlPatterns":[],"extraHeaders":{}},"score":100,"reportCategories":[{"name":"Performance","description":"These encapsulate your web app's current performance and opportunities to improve it.","audits":[{"id":"first-meaningful-paint","weight":5,"group":"perf-metric","result":{"score":94,"displayValue":"1,790 ms","rawValue":1790.1,"extendedInfo":{"value":{"timestamps":{"navStart":1486179379511,"fCP":1486181169577,"fMP":1486181169579,"onLoad":1486183845564,"endOfTrace":1486200178379},"timings":{"navStart":0,"fCP":1790.066,"fMP":1790.068,"onLoad":4466.053,"endOfTrace":20798.868},"fmpFellBack":false}},"scoringMode":"numeric","name":"first-meaningful-paint","description":"First meaningful paint","helpText":"First meaningful paint measures when the primary content of a page is visible. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/first-meaningful-paint)."},"score":94},{"id":"first-interactive","weight":5,"group":"perf-metric","result":{"score":84,"displayValue":"4,500 ms","rawValue":4502.306,"extendedInfo":{"value":{"timeInMs":4502.306,"timestamp":1486183881817}},"scoringMode":"numeric","name":"first-interactive","description":"First Interactive (beta)","helpText":"First Interactive marks the time at which the page is minimally interactive. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/first-interactive)."},"score":84},{"id":"consistently-interactive","weight":5,"group":"perf-metric","result":{"score":84,"displayValue":"4,500 ms","rawValue":4502.306,"extendedInfo":{"value":{"cpuQuietPeriod":{"start":1486183881.817,"end":1486200178.379},"networkQuietPeriod":{"start":1486183528.4919999,"end":1486200178.379},"cpuQuietPeriods":[{"start":1486183881.817,"end":1486200178.379}],"networkQuietPeriods":[{"start":1486183528.4919999,"end":1486200178.379}],"timestamp":1486183881817,"timeInMs":4502.306}},"scoringMode":"numeric","name":"consistently-interactive","description":"Consistently Interactive (beta)","helpText":"Consistently Interactive marks the time at which the page is fully interactive. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/consistently-interactive)."},"score":84},{"id":"speed-index-metric","weight":1,"group":"perf-metric","result":{"score":null,"displayValue":"","rawValue":null,"error":true,"debugString":"Audit error: Images have different sizes!","scoringMode":"numeric","name":"speed-index-metric","description":"Perceptual Speed Index","helpText":"Speed Index shows how quickly the contents of a page are visibly populated. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/speed-index)."},"score":0},{"id":"estimated-input-latency","weight":1,"group":"perf-metric","result":{"score":100,"displayValue":"16 ms","rawValue":16,"extendedInfo":{"value":[{"percentile":0.5,"time":16},{"percentile":0.75,"time":16},{"percentile":0.9,"time":16},{"percentile":0.99,"time":81.81819999999644},{"percentile":1,"time":208.29499999998006}]},"scoringMode":"numeric","name":"estimated-input-latency","description":"Estimated Input Latency","helpText":"The score above is an estimate of how long your app takes to respond to user input, in milliseconds. There is a 90% probability that a user encounters this amount of latency, or less. 10% of the time a user can expect additional latency. If your latency is higher than 50 ms, users may perceive your app as laggy. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/estimated-input-latency)."},"score":100},{"id":"link-blocking-first-paint","weight":0,"group":"perf-hint","result":{"score":0,"displayValue":"5 resources delayed first paint by 854 ms","rawValue":854,"extendedInfo":{"value":{"wastedMs":"854 ms","results":[{"url":"https://fonts.googleapis.com/css?family=Roboto:400,700","totalKb":"0.67 KB","totalMs":"832 ms"},{"url":"https://fonts.googleapis.com/icon?family=Material+Icons","totalKb":"0.36 KB","totalMs":"837 ms"},{"url":"https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css","totalKb":"18.44 KB","totalMs":"842 ms"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/css/app.css","totalKb":"0.2 KB","totalMs":"850 ms"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/css/feed.css","totalKb":"0.62 KB","totalMs":"854 ms"}]}},"scoringMode":"binary","informative":true,"name":"link-blocking-first-paint","description":"Reduce render-blocking stylesheets","helpText":"External stylesheets are blocking the first paint of your page. Consider delivering critical CSS via `\u003cstyle>` tags and deferring non-critical styles. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/blocking-resources).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Size (KB)"},{"type":"text","itemType":"text","text":"Delayed Paint By (ms)"}],"items":[[{"type":"url","text":"https://fonts.googleapis.com/css?family=Roboto:400,700"},{"type":"text","text":"0.67 KB"},{"type":"text","text":"832 ms"}],[{"type":"url","text":"https://fonts.googleapis.com/icon?family=Material+Icons"},{"type":"text","text":"0.36 KB"},{"type":"text","text":"837 ms"}],[{"type":"url","text":"https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css"},{"type":"text","text":"18.44 KB"},{"type":"text","text":"842 ms"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/css/app.css"},{"type":"text","text":"0.2 KB"},{"type":"text","text":"850 ms"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/css/feed.css"},{"type":"text","text":"0.62 KB"},{"type":"text","text":"854 ms"}]]}},"score":0},{"id":"script-blocking-first-paint","weight":0,"group":"perf-hint","result":{"score":100,"displayValue":"","rawValue":0,"extendedInfo":{"value":{"wastedMs":"0 ms","results":[]}},"scoringMode":"binary","informative":true,"name":"script-blocking-first-paint","description":"Reduce render-blocking scripts","helpText":"Script elements are blocking the first paint of your page. Consider inlining critical scripts and deferring non-critical ones. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/blocking-resources).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Size (KB)"},{"type":"text","itemType":"text","text":"Delayed Paint By (ms)"}],"items":[]}},"score":100},{"id":"uses-responsive-images","weight":0,"group":"perf-hint","result":{"score":0,"displayValue":"Potential savings of 489 KB (~2,870 ms)","rawValue":2870,"extendedInfo":{"value":{"wastedMs":2870,"wastedKb":489,"results":[{"url":"https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png","preview":{"type":"thumbnail","url":"https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png","mimeType":"image/png"},"totalBytes":291744,"wastedBytes":206363,"wastedPercent":70.73412511223414,"isWasteful":true,"wastedKb":"202 KB","wastedMs":"1,180 ms","totalKb":"285 KB","totalMs":"1,670 ms","potentialSavings":"202 KB (71%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A32%3A53.884Z.png?alt=media&token=aca0478e-23b6-45d9-90d7-594641c37b77","preview":{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A32%3A53.884Z.png?alt=media&token=aca0478e-23b6-45d9-90d7-594641c37b77","mimeType":"image/png"},"totalBytes":215495,"wastedBytes":60027,"wastedPercent":27.85544318857823,"isWasteful":true,"wastedKb":"59 KB","wastedMs":"340 ms","totalKb":"210 KB","totalMs":"1,230 ms","potentialSavings":"59 KB (28%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c","preview":{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c","mimeType":"image/png"},"totalBytes":157759,"wastedBytes":43944,"wastedPercent":27.85544318857823,"isWasteful":true,"wastedKb":"43 KB","wastedMs":"250 ms","totalKb":"154 KB","totalMs":"900 ms","potentialSavings":"43 KB (28%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0","preview":{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0","mimeType":"image/png"},"totalBytes":154974,"wastedBytes":43169,"wastedPercent":27.85544318857823,"isWasteful":true,"wastedKb":"42 KB","wastedMs":"250 ms","totalKb":"151 KB","totalMs":"890 ms","potentialSavings":"42 KB (28%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A42%3A19.478Z.png?alt=media&token=99f7a653-5780-411b-91c6-ca1a86b4a8a5","preview":{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A42%3A19.478Z.png?alt=media&token=99f7a653-5780-411b-91c6-ca1a86b4a8a5","mimeType":"image/png"},"totalBytes":145182,"wastedBytes":40441,"wastedPercent":27.85544318857823,"isWasteful":true,"wastedKb":"39 KB","wastedMs":"230 ms","totalKb":"142 KB","totalMs":"830 ms","potentialSavings":"39 KB (28%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A41%3A06.899Z.png?alt=media&token=ab32239e-a34f-4a94-880a-bc03dec7121b","preview":{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A41%3A06.899Z.png?alt=media&token=ab32239e-a34f-4a94-880a-bc03dec7121b","mimeType":"image/png"},"totalBytes":138792,"wastedBytes":38661,"wastedPercent":27.85544318857823,"isWasteful":true,"wastedKb":"38 KB","wastedMs":"220 ms","totalKb":"136 KB","totalMs":"790 ms","potentialSavings":"38 KB (28%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&token=60c2ac2a-de60-4ebc-b970-70264d96a80b","preview":{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&token=60c2ac2a-de60-4ebc-b970-70264d96a80b","mimeType":"image/png"},"totalBytes":136551,"wastedBytes":38037,"wastedPercent":27.85544318857823,"isWasteful":true,"wastedKb":"37 KB","wastedMs":"220 ms","totalKb":"133 KB","totalMs":"780 ms","potentialSavings":"37 KB (28%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&token=d0181e98-3ea9-499b-865e-8cec92fa1e33","preview":{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&token=d0181e98-3ea9-499b-865e-8cec92fa1e33","mimeType":"image/png"},"totalBytes":108988,"wastedBytes":30359,"wastedPercent":27.85544318857823,"isWasteful":true,"wastedKb":"30 KB","wastedMs":"170 ms","totalKb":"106 KB","totalMs":"620 ms","potentialSavings":"30 KB (28%)"}]}},"scoringMode":"binary","informative":true,"name":"uses-responsive-images","description":"Properly size images","helpText":"Serve images that are appropriately-sized to save cellular data and improve load time. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/oversized-images).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"thumbnail","text":""},{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Original"},{"type":"text","itemType":"text","text":"Potential Savings"}],"items":[[{"type":"thumbnail","url":"https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png","mimeType":"image/png"},{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png"},{"type":"text","text":"285 KB"},{"type":"text","text":"202 KB (71%)"}],[{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A32%3A53.884Z.png?alt=media&token=aca0478e-23b6-45d9-90d7-594641c37b77","mimeType":"image/png"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A32%3A53.884Z.png?alt=media&token=aca0478e-23b6-45d9-90d7-594641c37b77"},{"type":"text","text":"210 KB"},{"type":"text","text":"59 KB (28%)"}],[{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c","mimeType":"image/png"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c"},{"type":"text","text":"154 KB"},{"type":"text","text":"43 KB (28%)"}],[{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0","mimeType":"image/png"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0"},{"type":"text","text":"151 KB"},{"type":"text","text":"42 KB (28%)"}],[{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A42%3A19.478Z.png?alt=media&token=99f7a653-5780-411b-91c6-ca1a86b4a8a5","mimeType":"image/png"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A42%3A19.478Z.png?alt=media&token=99f7a653-5780-411b-91c6-ca1a86b4a8a5"},{"type":"text","text":"142 KB"},{"type":"text","text":"39 KB (28%)"}],[{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A41%3A06.899Z.png?alt=media&token=ab32239e-a34f-4a94-880a-bc03dec7121b","mimeType":"image/png"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A41%3A06.899Z.png?alt=media&token=ab32239e-a34f-4a94-880a-bc03dec7121b"},{"type":"text","text":"136 KB"},{"type":"text","text":"38 KB (28%)"}],[{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&token=60c2ac2a-de60-4ebc-b970-70264d96a80b","mimeType":"image/png"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&token=60c2ac2a-de60-4ebc-b970-70264d96a80b"},{"type":"text","text":"133 KB"},{"type":"text","text":"37 KB (28%)"}],[{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&token=d0181e98-3ea9-499b-865e-8cec92fa1e33","mimeType":"image/png"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&token=d0181e98-3ea9-499b-865e-8cec92fa1e33"},{"type":"text","text":"106 KB"},{"type":"text","text":"30 KB (28%)"}]]}},"score":0},{"id":"offscreen-images","weight":0,"group":"perf-hint","result":{"score":0,"displayValue":"Potential savings of 545 KB (~3,200 ms)","rawValue":3200,"extendedInfo":{"value":{"wastedMs":3200,"wastedKb":545,"results":[{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c","preview":{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c","mimeType":"image/png"},"requestStartTime":1486182.238294,"totalBytes":157759,"wastedBytes":157759,"wastedPercent":100,"wastedKb":"154 KB","wastedMs":"900 ms","totalKb":"154 KB","totalMs":"900 ms","potentialSavings":"154 KB (100%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0","preview":{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0","mimeType":"image/png"},"requestStartTime":1486182.244326,"totalBytes":154974,"wastedBytes":154974,"wastedPercent":100,"wastedKb":"151 KB","wastedMs":"890 ms","totalKb":"151 KB","totalMs":"890 ms","potentialSavings":"151 KB (100%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&token=60c2ac2a-de60-4ebc-b970-70264d96a80b","preview":{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&token=60c2ac2a-de60-4ebc-b970-70264d96a80b","mimeType":"image/png"},"requestStartTime":1486182.240525,"totalBytes":136551,"wastedBytes":136551,"wastedPercent":100,"wastedKb":"133 KB","wastedMs":"780 ms","totalKb":"133 KB","totalMs":"780 ms","potentialSavings":"133 KB (100%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&token=d0181e98-3ea9-499b-865e-8cec92fa1e33","preview":{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&token=d0181e98-3ea9-499b-865e-8cec92fa1e33","mimeType":"image/png"},"requestStartTime":1486182.248715,"totalBytes":108988,"wastedBytes":108988,"wastedPercent":100,"wastedKb":"106 KB","wastedMs":"620 ms","totalKb":"106 KB","totalMs":"620 ms","potentialSavings":"106 KB (100%)"}]}},"scoringMode":"binary","informative":true,"name":"offscreen-images","description":"Offscreen images","helpText":"Consider lazy-loading offscreen and hidden images to improve page load speed and time to interactive. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/offscreen-images).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"thumbnail","text":""},{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Original"},{"type":"text","itemType":"text","text":"Potential Savings"}],"items":[[{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c","mimeType":"image/png"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c"},{"type":"text","text":"154 KB"},{"type":"text","text":"154 KB (100%)"}],[{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0","mimeType":"image/png"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0"},{"type":"text","text":"151 KB"},{"type":"text","text":"151 KB (100%)"}],[{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&token=60c2ac2a-de60-4ebc-b970-70264d96a80b","mimeType":"image/png"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&token=60c2ac2a-de60-4ebc-b970-70264d96a80b"},{"type":"text","text":"133 KB"},{"type":"text","text":"133 KB (100%)"}],[{"type":"thumbnail","url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&token=d0181e98-3ea9-499b-865e-8cec92fa1e33","mimeType":"image/png"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&token=d0181e98-3ea9-499b-865e-8cec92fa1e33"},{"type":"text","text":"106 KB"},{"type":"text","text":"106 KB (100%)"}]]}},"score":0},{"id":"unminified-css","weight":0,"group":"perf-hint","result":{"score":100,"displayValue":"","rawValue":0,"extendedInfo":{"value":{"wastedMs":0,"wastedKb":0,"results":[]}},"scoringMode":"binary","informative":true,"name":"unminified-css","description":"Minify CSS","helpText":"Minifying CSS files can reduce network payload sizes. [Learn more](https://developers.google.com/speed/docs/insights/MinifyResources).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Original"},{"type":"text","itemType":"text","text":"Potential Savings"}],"items":[]}},"score":100},{"id":"unminified-javascript","weight":0,"group":"perf-hint","result":{"score":100,"displayValue":"","rawValue":0,"extendedInfo":{"value":{"wastedMs":0,"wastedKb":0,"results":[]}},"scoringMode":"binary","informative":true,"name":"unminified-javascript","description":"Minify JavaScript","helpText":"Minifying JavaScript files can reduce payload sizes and script parse time. [Learn more](https://developers.google.com/speed/docs/insights/MinifyResources).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Original"},{"type":"text","itemType":"text","text":"Potential Savings"}],"items":[]}},"score":100},{"id":"unused-css-rules","weight":0,"group":"perf-hint","result":{"score":90,"displayValue":"Potential savings of 17 KB (~100 ms)","rawValue":100,"extendedInfo":{"value":{"wastedMs":100,"wastedKb":17,"results":[{"url":"https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css","wastedBytes":17300,"wastedPercent":91.60692168866555,"totalBytes":18885,"wastedKb":"17 KB","wastedMs":"100 ms","totalKb":"18 KB","totalMs":"110 ms","potentialSavings":"17 KB (92%)"}]}},"scoringMode":"binary","informative":true,"name":"unused-css-rules","description":"Unused CSS rules","helpText":"Remove unused rules from stylesheets to reduce unnecessary bytes consumed by network activity. [Learn more](https://developers.google.com/speed/docs/insights/OptimizeCSSDelivery)","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Original"},{"type":"text","itemType":"text","text":"Potential Savings"}],"items":[[{"type":"url","text":"https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css"},{"type":"text","text":"18 KB"},{"type":"text","text":"17 KB (92%)"}]]}},"score":90},{"id":"uses-optimized-images","weight":0,"group":"perf-hint","result":{"score":100,"displayValue":"","rawValue":0,"extendedInfo":{"value":{"wastedMs":0,"wastedKb":0,"results":[]}},"scoringMode":"binary","informative":true,"name":"uses-optimized-images","description":"Optimize images","helpText":"Optimized images load faster and consume less cellular data. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/optimize-images).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"thumbnail","text":""},{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Original"},{"type":"text","itemType":"text","text":"Potential Savings"}],"items":[]}},"score":100},{"id":"uses-webp-images","weight":0,"group":"perf-hint","result":{"score":0,"displayValue":"Potential savings of 463 KB (~2,720 ms)","rawValue":2720,"extendedInfo":{"value":{"wastedMs":2720,"wastedKb":463,"results":[{"url":"https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png","fromProtocol":true,"isCrossOrigin":false,"preview":{"url":"https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png","mimeType":"image/png","type":"thumbnail"},"totalBytes":291744,"wastedBytes":233594,"wastedKb":"228 KB","wastedMs":"1,340 ms","totalKb":"285 KB","totalMs":"1,670 ms","potentialSavings":"228 KB (80%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A32%3A53.884Z.png?alt=media&token=aca0478e-23b6-45d9-90d7-594641c37b77","fromProtocol":true,"isCrossOrigin":true,"preview":{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A32%3A53.884Z.png?alt=media&token=aca0478e-23b6-45d9-90d7-594641c37b77","mimeType":"image/png","type":"thumbnail"},"totalBytes":215495,"wastedBytes":45509,"wastedKb":"44 KB","wastedMs":"260 ms","totalKb":"210 KB","totalMs":"1,230 ms","potentialSavings":"44 KB (21%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A42%3A19.478Z.png?alt=media&token=99f7a653-5780-411b-91c6-ca1a86b4a8a5","fromProtocol":true,"isCrossOrigin":true,"preview":{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A42%3A19.478Z.png?alt=media&token=99f7a653-5780-411b-91c6-ca1a86b4a8a5","mimeType":"image/png","type":"thumbnail"},"totalBytes":145182,"wastedBytes":33278,"wastedKb":"32 KB","wastedMs":"190 ms","totalKb":"142 KB","totalMs":"830 ms","potentialSavings":"32 KB (23%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&token=60c2ac2a-de60-4ebc-b970-70264d96a80b","fromProtocol":true,"isCrossOrigin":true,"preview":{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&token=60c2ac2a-de60-4ebc-b970-70264d96a80b","mimeType":"image/png","type":"thumbnail"},"totalBytes":136551,"wastedBytes":33257,"wastedKb":"32 KB","wastedMs":"190 ms","totalKb":"133 KB","totalMs":"780 ms","potentialSavings":"32 KB (24%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0","fromProtocol":true,"isCrossOrigin":true,"preview":{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0","mimeType":"image/png","type":"thumbnail"},"totalBytes":154974,"wastedBytes":33030,"wastedKb":"32 KB","wastedMs":"190 ms","totalKb":"151 KB","totalMs":"890 ms","potentialSavings":"32 KB (21%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&token=d0181e98-3ea9-499b-865e-8cec92fa1e33","fromProtocol":true,"isCrossOrigin":true,"preview":{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&token=d0181e98-3ea9-499b-865e-8cec92fa1e33","mimeType":"image/png","type":"thumbnail"},"totalBytes":108988,"wastedBytes":32258,"wastedKb":"32 KB","wastedMs":"180 ms","totalKb":"106 KB","totalMs":"620 ms","potentialSavings":"32 KB (30%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A41%3A06.899Z.png?alt=media&token=ab32239e-a34f-4a94-880a-bc03dec7121b","fromProtocol":true,"isCrossOrigin":true,"preview":{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A41%3A06.899Z.png?alt=media&token=ab32239e-a34f-4a94-880a-bc03dec7121b","mimeType":"image/png","type":"thumbnail"},"totalBytes":138792,"wastedBytes":32098,"wastedKb":"31 KB","wastedMs":"180 ms","totalKb":"136 KB","totalMs":"790 ms","potentialSavings":"31 KB (23%)"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c","fromProtocol":true,"isCrossOrigin":true,"preview":{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c","mimeType":"image/png","type":"thumbnail"},"totalBytes":157759,"wastedBytes":31403,"wastedKb":"31 KB","wastedMs":"180 ms","totalKb":"154 KB","totalMs":"900 ms","potentialSavings":"31 KB (20%)"}]}},"scoringMode":"binary","informative":true,"name":"uses-webp-images","description":"Serve images in next-gen formats","helpText":"Image formats like JPEG 2000, JPEG XR, and WebP often provide better compression than PNG or JPEG, which means faster downloads and less data consumption. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/webp).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"thumbnail","text":""},{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Original"},{"type":"text","itemType":"text","text":"Potential Savings"}],"items":[[{"url":"https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png","mimeType":"image/png","type":"thumbnail"},{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png"},{"type":"text","text":"285 KB"},{"type":"text","text":"228 KB (80%)"}],[{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A32%3A53.884Z.png?alt=media&token=aca0478e-23b6-45d9-90d7-594641c37b77","mimeType":"image/png","type":"thumbnail"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A32%3A53.884Z.png?alt=media&token=aca0478e-23b6-45d9-90d7-594641c37b77"},{"type":"text","text":"210 KB"},{"type":"text","text":"44 KB (21%)"}],[{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A42%3A19.478Z.png?alt=media&token=99f7a653-5780-411b-91c6-ca1a86b4a8a5","mimeType":"image/png","type":"thumbnail"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A42%3A19.478Z.png?alt=media&token=99f7a653-5780-411b-91c6-ca1a86b4a8a5"},{"type":"text","text":"142 KB"},{"type":"text","text":"32 KB (23%)"}],[{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&token=60c2ac2a-de60-4ebc-b970-70264d96a80b","mimeType":"image/png","type":"thumbnail"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&token=60c2ac2a-de60-4ebc-b970-70264d96a80b"},{"type":"text","text":"133 KB"},{"type":"text","text":"32 KB (24%)"}],[{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0","mimeType":"image/png","type":"thumbnail"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0"},{"type":"text","text":"151 KB"},{"type":"text","text":"32 KB (21%)"}],[{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&token=d0181e98-3ea9-499b-865e-8cec92fa1e33","mimeType":"image/png","type":"thumbnail"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&token=d0181e98-3ea9-499b-865e-8cec92fa1e33"},{"type":"text","text":"106 KB"},{"type":"text","text":"32 KB (30%)"}],[{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A41%3A06.899Z.png?alt=media&token=ab32239e-a34f-4a94-880a-bc03dec7121b","mimeType":"image/png","type":"thumbnail"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A41%3A06.899Z.png?alt=media&token=ab32239e-a34f-4a94-880a-bc03dec7121b"},{"type":"text","text":"136 KB"},{"type":"text","text":"31 KB (23%)"}],[{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c","mimeType":"image/png","type":"thumbnail"},{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c"},{"type":"text","text":"154 KB"},{"type":"text","text":"31 KB (20%)"}]]}},"score":0},{"id":"uses-request-compression","weight":0,"group":"perf-hint","result":{"score":90,"displayValue":"Potential savings of 1 KB (~10 ms)","rawValue":10,"extendedInfo":{"value":{"wastedMs":10,"wastedKb":1,"results":[{"url":"https://facebookfeed-neel.firebaseio.com/posts.json","totalBytes":2181,"wastedBytes":1438,"wastedKb":"1 KB","wastedMs":"10 ms","totalKb":"2 KB","totalMs":"10 ms","potentialSavings":"1 KB (66%)"}]}},"scoringMode":"binary","informative":true,"name":"uses-request-compression","description":"Enable text compression","helpText":"Text-based responses should be served with compression (gzip, deflate or brotli) to minimize total network bytes. [Learn more](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/optimize-encoding-and-transfer).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"Uncompressed resource URL"},{"type":"text","itemType":"text","text":"Original"},{"type":"text","itemType":"text","text":"GZIP Savings"}],"items":[[{"type":"url","text":"https://facebookfeed-neel.firebaseio.com/posts.json"},{"type":"text","text":"2 KB"},{"type":"text","text":"1 KB (66%)"}]]}},"score":90},{"id":"time-to-first-byte","weight":0,"group":"perf-hint","result":{"score":true,"displayValue":"560 ms","rawValue":564.345,"debugString":"","extendedInfo":{"value":{"wastedMs":-35.65499999999997}},"scoringMode":"binary","informative":true,"name":"time-to-first-byte","description":"Keep server response times low (TTFB)","helpText":"Time To First Byte identifies the time at which your server sends a response. [Learn more](https://developers.google.com/web/tools/chrome-devtools/network-performance/issues)."},"score":100},{"id":"redirects","weight":0,"group":"perf-hint","result":{"score":100,"displayValue":"0 ms","rawValue":0,"extendedInfo":{"value":{"wastedMs":0}},"scoringMode":"binary","name":"redirects","description":"Avoids page redirects","helpText":"Redirects introduce additional delays before the page can be loaded. [Learn more](https://developers.google.com/speed/docs/insights/AvoidRedirects).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"text","text":"Redirected URL"},{"type":"text","itemType":"text","text":"Time for Redirect"}],"items":[]}},"score":100},{"id":"uses-rel-preload","weight":0,"group":"perf-hint","result":{"score":100,"displayValue":"0 ms","rawValue":0,"extendedInfo":{"value":[]},"scoringMode":"numeric","informative":true,"name":"uses-rel-preload","description":"Preload key requests","helpText":"Consider using \u003clink rel=preload> to prioritize fetching late-discovered resources sooner [Learn more](https://developers.google.com/web/updates/2016/03/link-rel-preload).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Potential Savings"}],"items":[]}},"score":100},{"id":"total-byte-weight","weight":0,"group":"perf-info","result":{"score":100,"displayValue":"Total size was 404 KB","rawValue":413236,"extendedInfo":{"value":{"results":[{"url":"https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png","totalBytes":292040,"totalKb":"285 KB","totalMs":"1,670 ms"},{"url":"https://fonts.gstatic.com/s/materialicons/v36/flUhRq6tzZclQEJ-Vdg-IuiaDsNcIhQ8tQ.woff2","totalBytes":49172,"totalKb":"48 KB","totalMs":"280 ms"},{"url":"https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css","totalBytes":18885,"totalKb":"18 KB","totalMs":"110 ms"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/material.min.js","totalBytes":11790,"totalKb":"12 KB","totalMs":"70 ms"},{"url":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu4mxKKTU1Kg.woff2","totalBytes":10814,"totalKb":"11 KB","totalMs":"60 ms"},{"url":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu7GxKKTU1Kvnz.woff2","totalBytes":8118,"totalKb":"8 KB","totalMs":"50 ms"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/fetch.js","totalBytes":3426,"totalKb":"3 KB","totalMs":"20 ms"},{"url":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu7WxKKTU1Kvnz.woff2","totalBytes":3375,"totalKb":"3 KB","totalMs":"20 ms"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/feed.js","totalBytes":2933,"totalKb":"3 KB","totalMs":"20 ms"},{"url":"https://facebookfeed-neel.firebaseio.com/posts.json","totalBytes":2515,"totalKb":"2 KB","totalMs":"10 ms"}],"totalCompletedRequests":27}},"scoringMode":"numeric","name":"total-byte-weight","description":"Avoids enormous network payloads","helpText":"Large network payloads cost users real money and are highly correlated with long load times. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/network-payloads).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Total Size"},{"type":"text","itemType":"text","text":"Transfer Time"}],"items":[[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png"},{"type":"text","text":"285 KB"},{"type":"text","text":"1,670 ms"}],[{"type":"url","text":"https://fonts.gstatic.com/s/materialicons/v36/flUhRq6tzZclQEJ-Vdg-IuiaDsNcIhQ8tQ.woff2"},{"type":"text","text":"48 KB"},{"type":"text","text":"280 ms"}],[{"type":"url","text":"https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css"},{"type":"text","text":"18 KB"},{"type":"text","text":"110 ms"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/material.min.js"},{"type":"text","text":"12 KB"},{"type":"text","text":"70 ms"}],[{"type":"url","text":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu4mxKKTU1Kg.woff2"},{"type":"text","text":"11 KB"},{"type":"text","text":"60 ms"}],[{"type":"url","text":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu7GxKKTU1Kvnz.woff2"},{"type":"text","text":"8 KB"},{"type":"text","text":"50 ms"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/fetch.js"},{"type":"text","text":"3 KB"},{"type":"text","text":"20 ms"}],[{"type":"url","text":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu7WxKKTU1Kvnz.woff2"},{"type":"text","text":"3 KB"},{"type":"text","text":"20 ms"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/feed.js"},{"type":"text","text":"3 KB"},{"type":"text","text":"20 ms"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseio.com/posts.json"},{"type":"text","text":"2 KB"},{"type":"text","text":"10 ms"}]]}},"score":100},{"id":"uses-long-cache-ttl","weight":0,"group":"perf-info","result":{"score":77,"displayValue":"12 assets found","rawValue":254380.39999999997,"extendedInfo":{"value":{"results":[{"url":"https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png","cacheControl":{"max-age":3600},"cacheLifetimeInSeconds":3600,"cacheLifetimeDisplay":"1 h","cacheHitProbability":0.2,"totalKb":"285 KB","totalBytes":292040,"wastedBytes":233632},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/material.min.js","cacheControl":{"max-age":3600},"cacheLifetimeInSeconds":3600,"cacheLifetimeDisplay":"1 h","cacheHitProbability":0.2,"totalKb":"12 KB","totalBytes":11790,"wastedBytes":9432},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/fetch.js","cacheControl":{"max-age":3600},"cacheLifetimeInSeconds":3600,"cacheLifetimeDisplay":"1 h","cacheHitProbability":0.2,"totalKb":"3 KB","totalBytes":3426,"wastedBytes":2740.8},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/feed.js","cacheControl":{"max-age":3600},"cacheLifetimeInSeconds":3600,"cacheLifetimeDisplay":"1 h","cacheHitProbability":0.2,"totalKb":"3 KB","totalBytes":2933,"wastedBytes":2346.4},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/promise.js","cacheControl":{"max-age":3600},"cacheLifetimeInSeconds":3600,"cacheLifetimeDisplay":"1 h","cacheHitProbability":0.2,"totalKb":"2 KB","totalBytes":2448,"wastedBytes":1958.4},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/idb.js","cacheControl":{"max-age":3600},"cacheLifetimeInSeconds":3600,"cacheLifetimeDisplay":"1 h","cacheHitProbability":0.2,"totalKb":"2 KB","totalBytes":1858,"wastedBytes":1486.4},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/app.js","cacheControl":{"max-age":3600},"cacheLifetimeInSeconds":3600,"cacheLifetimeDisplay":"1 h","cacheHitProbability":0.2,"totalKb":"1 KB","totalBytes":1323,"wastedBytes":1058.4},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/utility.js","cacheControl":{"max-age":3600},"cacheLifetimeInSeconds":3600,"cacheLifetimeDisplay":"1 h","cacheHitProbability":0.2,"totalKb":"1 KB","totalBytes":785,"wastedBytes":628},{"url":"https://facebookfeed-neel.firebaseapp.com/src/css/feed.css","cacheControl":{"max-age":3600},"cacheLifetimeInSeconds":3600,"cacheLifetimeDisplay":"1 h","cacheHitProbability":0.2,"totalKb":"1 KB","totalBytes":639,"wastedBytes":511.20000000000005},{"url":"https://facebookfeed-neel.firebaseapp.com/src/css/app.css","cacheControl":{"max-age":3600},"cacheLifetimeInSeconds":3600,"cacheLifetimeDisplay":"1 h","cacheHitProbability":0.2,"totalKb":"0 KB","totalBytes":207,"wastedBytes":165.60000000000002},{"url":"https://fonts.googleapis.com/css?family=Roboto:400,700","cacheControl":{"private":true,"max-age":86400,"stale-while-revalidate":"604800"},"cacheLifetimeInSeconds":86400,"cacheLifetimeDisplay":"1 d","cacheHitProbability":0.6,"totalKb":"1 KB","totalBytes":681,"wastedBytes":272.40000000000003},{"url":"https://fonts.googleapis.com/icon?family=Material+Icons","cacheControl":{"private":true,"max-age":86400,"stale-while-revalidate":"604800"},"cacheLifetimeInSeconds":86400,"cacheLifetimeDisplay":"1 d","cacheHitProbability":0.6,"totalKb":"0 KB","totalBytes":372,"wastedBytes":148.8}],"queryStringCount":2}},"scoringMode":"numeric","name":"uses-long-cache-ttl","description":"Uses inefficient cache policy on static assets","helpText":"A long cache lifetime can speed up repeat visits to your page. [Learn more](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching#cache-control).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Cache TTL"},{"type":"text","itemType":"text","text":"Size (KB)"}],"items":[[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png"},{"type":"text","text":"1 h"},{"type":"text","text":"285 KB"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/material.min.js"},{"type":"text","text":"1 h"},{"type":"text","text":"12 KB"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/fetch.js"},{"type":"text","text":"1 h"},{"type":"text","text":"3 KB"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/feed.js"},{"type":"text","text":"1 h"},{"type":"text","text":"3 KB"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/promise.js"},{"type":"text","text":"1 h"},{"type":"text","text":"2 KB"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/idb.js"},{"type":"text","text":"1 h"},{"type":"text","text":"2 KB"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/app.js"},{"type":"text","text":"1 h"},{"type":"text","text":"1 KB"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/utility.js"},{"type":"text","text":"1 h"},{"type":"text","text":"1 KB"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/css/feed.css"},{"type":"text","text":"1 h"},{"type":"text","text":"1 KB"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/css/app.css"},{"type":"text","text":"1 h"},{"type":"text","text":"0 KB"}],[{"type":"url","text":"https://fonts.googleapis.com/css?family=Roboto:400,700"},{"type":"text","text":"1 d"},{"type":"text","text":"1 KB"}],[{"type":"url","text":"https://fonts.googleapis.com/icon?family=Material+Icons"},{"type":"text","text":"1 d"},{"type":"text","text":"0 KB"}]]}},"score":77},{"id":"dom-size","weight":0,"group":"perf-info","result":{"score":100,"displayValue":"207 nodes","rawValue":207,"extendedInfo":{"value":[{"title":"Total DOM Nodes","value":"207","target":"\u003c 1,500 nodes"},{"title":"DOM Depth","value":"13","snippet":"html.mdl-js >\n  body >\n    div#app >\n      div.mdl-layout__container >\n        div.mdl-layout.mdl-js-layout.mdl-layout--fixed-header.has-drawer.is-small-screen.is-upgraded >\n          main.mdl-layout__content.mat-typography >\n            div#create-post >\n              form >\n                div.input-section >\n                  div#location-loader.mdl-spinner.mdl-js-spinner.is-active.is-upgraded >\n                    div.mdl-spinner__layer.mdl-spinner__layer-1 >\n                      div.mdl-spinner__circle-clipper.mdl-spinner__left >\n                        div.mdl-spinner__circle","target":"\u003c 32"},{"title":"Maximum Children","value":"25","snippet":"Element with most children:\nhead","target":"\u003c 60 nodes"}]},"scoringMode":"numeric","name":"dom-size","description":"Avoids an excessive DOM size","helpText":"Browser engineers recommend pages contain fewer than ~1,500 DOM nodes. The sweet spot is a tree depth \u003c 32 elements and fewer than 60 children/parent element. A large DOM can increase memory usage, cause longer [style calculations](https://developers.google.com/web/fundamentals/performance/rendering/reduce-the-scope-and-complexity-of-style-calculations), and produce costly [layout reflows](https://developers.google.com/speed/articles/reflow). [Learn more](https://developers.google.com/web/fundamentals/performance/rendering/).","details":{"type":"cards","header":{"type":"text","text":"View details"},"items":[{"title":"Total DOM Nodes","value":"207","target":"\u003c 1,500 nodes"},{"title":"DOM Depth","value":"13","snippet":"html.mdl-js >\n  body >\n    div#app >\n      div.mdl-layout__container >\n        div.mdl-layout.mdl-js-layout.mdl-layout--fixed-header.has-drawer.is-small-screen.is-upgraded >\n          main.mdl-layout__content.mat-typography >\n            div#create-post >\n              form >\n                div.input-section >\n                  div#location-loader.mdl-spinner.mdl-js-spinner.is-active.is-upgraded >\n                    div.mdl-spinner__layer.mdl-spinner__layer-1 >\n                      div.mdl-spinner__circle-clipper.mdl-spinner__left >\n                        div.mdl-spinner__circle","target":"\u003c 32"},{"title":"Maximum Children","value":"25","snippet":"Element with most children:\nhead","target":"\u003c 60 nodes"}]}},"score":100},{"id":"critical-request-chains","weight":0,"group":"perf-info","result":{"score":false,"displayValue":"15","rawValue":false,"extendedInfo":{"value":{"chains":{"34A2F958E8DA35C4C3C68A28746FC5F7":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/","startTime":1486179.383232,"endTime":1486179.966296,"responseReceivedTime":1486179.9554990001,"transferSize":1855},"children":{"15080.62":{"request":{"url":"https://fonts.googleapis.com/css?family=Roboto:400,700","startTime":1486180.072954,"endTime":1486180.904868,"responseReceivedTime":1486180.647064,"transferSize":681},"children":{}},"15080.63":{"request":{"url":"https://fonts.googleapis.com/icon?family=Material+Icons","startTime":1486180.073977,"endTime":1486180.909894,"responseReceivedTime":1486180.654143,"transferSize":372},"children":{}},"15080.64":{"request":{"url":"https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css","startTime":1486180.07529,"endTime":1486180.914856,"responseReceivedTime":1486180.661993,"transferSize":18885},"children":{}},"15080.65":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/css/app.css","startTime":1486180.083797,"endTime":1486180.923173,"responseReceivedTime":1486180.670025,"transferSize":207},"children":{}},"15080.66":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/css/feed.css","startTime":1486180.084763,"endTime":1486180.927271,"responseReceivedTime":1486180.678015,"transferSize":639},"children":{}},"15080.69":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/promise.js","startTime":1486180.678962,"endTime":1486181.266579,"responseReceivedTime":1486181.258414,"transferSize":2448},"children":{}},"15080.70":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/fetch.js","startTime":1486180.775301,"endTime":1486181.409872,"responseReceivedTime":1486181.3534960002,"transferSize":3426},"children":{}},"15080.71":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/idb.js","startTime":1486180.775458,"endTime":1486181.401772,"responseReceivedTime":1486181.3614909998,"transferSize":1858},"children":{}},"15080.72":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/utility.js","startTime":1486180.775576,"endTime":1486181.370249,"responseReceivedTime":1486181.3694820001,"transferSize":785},"children":{}},"15080.73":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/app.js","startTime":1486180.775682,"endTime":1486181.397222,"responseReceivedTime":1486181.395681,"transferSize":1323},"children":{}},"15080.74":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/feed.js","startTime":1486180.775786,"endTime":1486181.417822,"responseReceivedTime":1486181.396312,"transferSize":2933},"children":{}},"15080.89":{"request":{"url":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu4mxKKTU1Kg.woff2","startTime":1486181.128047,"endTime":1486181.909994,"responseReceivedTime":1486181.760324,"transferSize":10814},"children":{}},"15080.97":{"request":{"url":"https://fonts.gstatic.com/s/materialicons/v36/flUhRq6tzZclQEJ-Vdg-IuiaDsNcIhQ8tQ.woff2","startTime":1486181.134527,"endTime":1486182.395296,"responseReceivedTime":1486181.760996,"transferSize":49172},"children":{}},"15080.88":{"request":{"url":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu7GxKKTU1Kvnz.woff2","startTime":1486182.275052,"endTime":1486182.975742,"responseReceivedTime":1486182.895545,"transferSize":8118},"children":{}},"15080.87":{"request":{"url":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu7WxKKTU1Kvnz.woff2","startTime":1486183.015248,"endTime":1486183.67418,"responseReceivedTime":1486183.643009,"transferSize":3375},"children":{}}}}},"longestChain":{"duration":4290.948000038043,"length":2,"transferSize":3375}}},"scoringMode":"binary","informative":true,"name":"critical-request-chains","description":"Critical Request Chains","helpText":"The Critical Request Chains below show you what resources are issued with a high priority. Consider reducing the length of chains, reducing the download size of resources, or deferring the download of unnecessary resources to improve page load. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/critical-request-chains).","details":{"type":"criticalrequestchain","header":{"type":"text","text":"View critical network waterfall:"},"chains":{"34A2F958E8DA35C4C3C68A28746FC5F7":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/","startTime":1486179.383232,"endTime":1486179.966296,"responseReceivedTime":1486179.9554990001,"transferSize":1855},"children":{"15080.62":{"request":{"url":"https://fonts.googleapis.com/css?family=Roboto:400,700","startTime":1486180.072954,"endTime":1486180.904868,"responseReceivedTime":1486180.647064,"transferSize":681},"children":{}},"15080.63":{"request":{"url":"https://fonts.googleapis.com/icon?family=Material+Icons","startTime":1486180.073977,"endTime":1486180.909894,"responseReceivedTime":1486180.654143,"transferSize":372},"children":{}},"15080.64":{"request":{"url":"https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css","startTime":1486180.07529,"endTime":1486180.914856,"responseReceivedTime":1486180.661993,"transferSize":18885},"children":{}},"15080.65":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/css/app.css","startTime":1486180.083797,"endTime":1486180.923173,"responseReceivedTime":1486180.670025,"transferSize":207},"children":{}},"15080.66":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/css/feed.css","startTime":1486180.084763,"endTime":1486180.927271,"responseReceivedTime":1486180.678015,"transferSize":639},"children":{}},"15080.69":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/promise.js","startTime":1486180.678962,"endTime":1486181.266579,"responseReceivedTime":1486181.258414,"transferSize":2448},"children":{}},"15080.70":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/fetch.js","startTime":1486180.775301,"endTime":1486181.409872,"responseReceivedTime":1486181.3534960002,"transferSize":3426},"children":{}},"15080.71":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/idb.js","startTime":1486180.775458,"endTime":1486181.401772,"responseReceivedTime":1486181.3614909998,"transferSize":1858},"children":{}},"15080.72":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/utility.js","startTime":1486180.775576,"endTime":1486181.370249,"responseReceivedTime":1486181.3694820001,"transferSize":785},"children":{}},"15080.73":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/app.js","startTime":1486180.775682,"endTime":1486181.397222,"responseReceivedTime":1486181.395681,"transferSize":1323},"children":{}},"15080.74":{"request":{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/feed.js","startTime":1486180.775786,"endTime":1486181.417822,"responseReceivedTime":1486181.396312,"transferSize":2933},"children":{}},"15080.89":{"request":{"url":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu4mxKKTU1Kg.woff2","startTime":1486181.128047,"endTime":1486181.909994,"responseReceivedTime":1486181.760324,"transferSize":10814},"children":{}},"15080.97":{"request":{"url":"https://fonts.gstatic.com/s/materialicons/v36/flUhRq6tzZclQEJ-Vdg-IuiaDsNcIhQ8tQ.woff2","startTime":1486181.134527,"endTime":1486182.395296,"responseReceivedTime":1486181.760996,"transferSize":49172},"children":{}},"15080.88":{"request":{"url":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu7GxKKTU1Kvnz.woff2","startTime":1486182.275052,"endTime":1486182.975742,"responseReceivedTime":1486182.895545,"transferSize":8118},"children":{}},"15080.87":{"request":{"url":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu7WxKKTU1Kvnz.woff2","startTime":1486183.015248,"endTime":1486183.67418,"responseReceivedTime":1486183.643009,"transferSize":3375},"children":{}}}}},"longestChain":{"duration":4290.948000038043,"length":2,"transferSize":3375}}},"score":0},{"id":"network-requests","weight":0,"result":{"score":100,"displayValue":"27","rawValue":27,"extendedInfo":{"value":[{"url":"https://facebookfeed-neel.firebaseapp.com/","startTime":0,"endTime":583.0639998894185,"transferSize":1855,"statusCode":200,"mimeType":"text/html","resourceType":"document"},{"url":"https://fonts.googleapis.com/css?family=Roboto:400,700","startTime":689.7219999227673,"endTime":1521.6359999030828,"transferSize":681,"statusCode":200,"mimeType":"text/css","resourceType":"stylesheet"},{"url":"https://fonts.googleapis.com/icon?family=Material+Icons","startTime":690.7450000289828,"endTime":1526.661999989301,"transferSize":372,"statusCode":200,"mimeType":"text/css","resourceType":"stylesheet"},{"url":"https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css","startTime":692.0580000150949,"endTime":1531.6240000538528,"transferSize":18885,"statusCode":200,"mimeType":"text/css","resourceType":"stylesheet"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/css/app.css","startTime":700.565000064671,"endTime":1539.941000053659,"transferSize":207,"statusCode":200,"mimeType":"text/css","resourceType":"stylesheet"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/css/feed.css","startTime":701.530999969691,"endTime":1544.0390000585467,"transferSize":639,"statusCode":200,"mimeType":"text/css","resourceType":"stylesheet"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png","startTime":1768.6799999792129,"endTime":4379.0539999026805,"transferSize":292040,"statusCode":200,"mimeType":"image/png","resourceType":"image"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/material.min.js","startTime":1987.2669999022037,"endTime":2766.512000001967,"transferSize":11790,"statusCode":200,"mimeType":"application/javascript","resourceType":"script"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/promise.js","startTime":1295.729999896139,"endTime":1883.3469999954104,"transferSize":2448,"statusCode":200,"mimeType":"application/javascript","resourceType":"script"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/fetch.js","startTime":1392.0690000522882,"endTime":2026.6400000546128,"transferSize":3426,"statusCode":200,"mimeType":"application/javascript","resourceType":"script"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/idb.js","startTime":1392.2259998507798,"endTime":2018.5399998445064,"transferSize":1858,"statusCode":200,"mimeType":"application/javascript","resourceType":"script"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/utility.js","startTime":1392.344000050798,"endTime":1987.0169998612255,"transferSize":785,"statusCode":200,"mimeType":"application/javascript","resourceType":"script"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/app.js","startTime":1392.4499999266118,"endTime":2013.9899998903275,"transferSize":1323,"statusCode":200,"mimeType":"application/javascript","resourceType":"script"},{"url":"https://facebookfeed-neel.firebaseapp.com/src/js/feed.js","startTime":1392.5540000200272,"endTime":2034.5900000538677,"transferSize":2933,"statusCode":200,"mimeType":"application/javascript","resourceType":"script"},{"url":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu4mxKKTU1Kg.woff2","startTime":1744.8149998672307,"endTime":2526.7620000522584,"transferSize":10814,"statusCode":200,"mimeType":"font/woff2","resourceType":"font"},{"url":"https://fonts.gstatic.com/s/materialicons/v36/flUhRq6tzZclQEJ-Vdg-IuiaDsNcIhQ8tQ.woff2","startTime":1751.2949998490512,"endTime":3012.063999893144,"transferSize":49172,"statusCode":200,"mimeType":"font/woff2","resourceType":"font"},{"url":"https://facebookfeed-neel.firebaseio.com/posts.json","startTime":2071.6989999637008,"endTime":2820.968999993056,"transferSize":2515,"statusCode":200,"mimeType":"application/json","resourceType":"fetch"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c","startTime":2855.061999987811,"endTime":3683.9959998615086,"transferSize":0,"statusCode":200,"mimeType":"image/png","resourceType":"image"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&token=60c2ac2a-de60-4ebc-b970-70264d96a80b","startTime":2857.2929999791086,"endTime":3708.718999987468,"transferSize":0,"statusCode":200,"mimeType":"image/png","resourceType":"image"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0","startTime":2861.094000050798,"endTime":3773.873999947682,"transferSize":0,"statusCode":200,"mimeType":"image/png","resourceType":"image"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&token=d0181e98-3ea9-499b-865e-8cec92fa1e33","startTime":2865.482999943197,"endTime":3844.9899998959154,"transferSize":0,"statusCode":200,"mimeType":"image/png","resourceType":"image"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A42%3A19.478Z.png?alt=media&token=99f7a653-5780-411b-91c6-ca1a86b4a8a5","startTime":2868.502999888733,"endTime":3849.0140000358224,"transferSize":0,"statusCode":200,"mimeType":"image/png","resourceType":"image"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A32%3A53.884Z.png?alt=media&token=aca0478e-23b6-45d9-90d7-594641c37b77","startTime":2871.157999848947,"endTime":4056.5939999651164,"transferSize":0,"statusCode":200,"mimeType":"image/png","resourceType":"image"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A41%3A06.899Z.png?alt=media&token=ab32239e-a34f-4a94-880a-bc03dec7121b","startTime":2906.4879999496043,"endTime":4145.259999902919,"transferSize":0,"statusCode":200,"mimeType":"image/png","resourceType":"image"},{"url":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu7GxKKTU1Kvnz.woff2","startTime":2891.8200000189245,"endTime":3592.509999871254,"transferSize":8118,"statusCode":200,"mimeType":"font/woff2","resourceType":"font"},{"url":"chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/wrs_env.js","startTime":3320.219999877736,"endTime":3495.8009999245405,"transferSize":0,"statusCode":200,"mimeType":"application/javascript","resourceType":"script"},{"url":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu7WxKKTU1Kvnz.woff2","startTime":3632.0159998722374,"endTime":4290.948000038043,"transferSize":3375,"statusCode":200,"mimeType":"font/woff2","resourceType":"font"}]},"scoringMode":"binary","informative":true,"name":"network-requests","description":"Network Requests","helpText":"Lists the network requests that were made during page load.","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"ms","text":"Start Time"},{"type":"text","itemType":"ms","text":"End Time"},{"type":"text","itemType":"bytes","text":"Transfer Size"},{"type":"text","itemType":"text","text":"Status Code"},{"type":"text","itemType":"text","text":"MIME Type"},{"type":"text","itemType":"text","text":"Resource Type"}],"items":[[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/"},{"type":"ms","text":0},{"type":"ms","text":583.0639998894185},{"type":"bytes","text":1855},{"type":"text","text":200},{"type":"text","text":"text/html"},{"type":"text","text":"document"}],[{"type":"url","text":"https://fonts.googleapis.com/css?family=Roboto:400,700"},{"type":"ms","text":689.7219999227673},{"type":"ms","text":1521.6359999030828},{"type":"bytes","text":681},{"type":"text","text":200},{"type":"text","text":"text/css"},{"type":"text","text":"stylesheet"}],[{"type":"url","text":"https://fonts.googleapis.com/icon?family=Material+Icons"},{"type":"ms","text":690.7450000289828},{"type":"ms","text":1526.661999989301},{"type":"bytes","text":372},{"type":"text","text":200},{"type":"text","text":"text/css"},{"type":"text","text":"stylesheet"}],[{"type":"url","text":"https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css"},{"type":"ms","text":692.0580000150949},{"type":"ms","text":1531.6240000538528},{"type":"bytes","text":18885},{"type":"text","text":200},{"type":"text","text":"text/css"},{"type":"text","text":"stylesheet"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/css/app.css"},{"type":"ms","text":700.565000064671},{"type":"ms","text":1539.941000053659},{"type":"bytes","text":207},{"type":"text","text":200},{"type":"text","text":"text/css"},{"type":"text","text":"stylesheet"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/css/feed.css"},{"type":"ms","text":701.530999969691},{"type":"ms","text":1544.0390000585467},{"type":"bytes","text":639},{"type":"text","text":200},{"type":"text","text":"text/css"},{"type":"text","text":"stylesheet"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/images/pwa.png"},{"type":"ms","text":1768.6799999792129},{"type":"ms","text":4379.0539999026805},{"type":"bytes","text":292040},{"type":"text","text":200},{"type":"text","text":"image/png"},{"type":"text","text":"image"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/material.min.js"},{"type":"ms","text":1987.2669999022037},{"type":"ms","text":2766.512000001967},{"type":"bytes","text":11790},{"type":"text","text":200},{"type":"text","text":"application/javascript"},{"type":"text","text":"script"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/promise.js"},{"type":"ms","text":1295.729999896139},{"type":"ms","text":1883.3469999954104},{"type":"bytes","text":2448},{"type":"text","text":200},{"type":"text","text":"application/javascript"},{"type":"text","text":"script"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/fetch.js"},{"type":"ms","text":1392.0690000522882},{"type":"ms","text":2026.6400000546128},{"type":"bytes","text":3426},{"type":"text","text":200},{"type":"text","text":"application/javascript"},{"type":"text","text":"script"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/idb.js"},{"type":"ms","text":1392.2259998507798},{"type":"ms","text":2018.5399998445064},{"type":"bytes","text":1858},{"type":"text","text":200},{"type":"text","text":"application/javascript"},{"type":"text","text":"script"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/utility.js"},{"type":"ms","text":1392.344000050798},{"type":"ms","text":1987.0169998612255},{"type":"bytes","text":785},{"type":"text","text":200},{"type":"text","text":"application/javascript"},{"type":"text","text":"script"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/app.js"},{"type":"ms","text":1392.4499999266118},{"type":"ms","text":2013.9899998903275},{"type":"bytes","text":1323},{"type":"text","text":200},{"type":"text","text":"application/javascript"},{"type":"text","text":"script"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/feed.js"},{"type":"ms","text":1392.5540000200272},{"type":"ms","text":2034.5900000538677},{"type":"bytes","text":2933},{"type":"text","text":200},{"type":"text","text":"application/javascript"},{"type":"text","text":"script"}],[{"type":"url","text":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu4mxKKTU1Kg.woff2"},{"type":"ms","text":1744.8149998672307},{"type":"ms","text":2526.7620000522584},{"type":"bytes","text":10814},{"type":"text","text":200},{"type":"text","text":"font/woff2"},{"type":"text","text":"font"}],[{"type":"url","text":"https://fonts.gstatic.com/s/materialicons/v36/flUhRq6tzZclQEJ-Vdg-IuiaDsNcIhQ8tQ.woff2"},{"type":"ms","text":1751.2949998490512},{"type":"ms","text":3012.063999893144},{"type":"bytes","text":49172},{"type":"text","text":200},{"type":"text","text":"font/woff2"},{"type":"text","text":"font"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseio.com/posts.json"},{"type":"ms","text":2071.6989999637008},{"type":"ms","text":2820.968999993056},{"type":"bytes","text":2515},{"type":"text","text":200},{"type":"text","text":"application/json"},{"type":"text","text":"fetch"}],[{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c"},{"type":"ms","text":2855.061999987811},{"type":"ms","text":3683.9959998615086},{"type":"bytes","text":0},{"type":"text","text":200},{"type":"text","text":"image/png"},{"type":"text","text":"image"}],[{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A45%3A15.468Z.png?alt=media&token=60c2ac2a-de60-4ebc-b970-70264d96a80b"},{"type":"ms","text":2857.2929999791086},{"type":"ms","text":3708.718999987468},{"type":"bytes","text":0},{"type":"text","text":200},{"type":"text","text":"image/png"},{"type":"text","text":"image"}],[{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A44%3A20.265Z.png?alt=media&token=c0e7e5b4-b4b4-4069-ad5b-547e1234bcb0"},{"type":"ms","text":2861.094000050798},{"type":"ms","text":3773.873999947682},{"type":"bytes","text":0},{"type":"text","text":200},{"type":"text","text":"image/png"},{"type":"text","text":"image"}],[{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A43%3A05.377Z.png?alt=media&token=d0181e98-3ea9-499b-865e-8cec92fa1e33"},{"type":"ms","text":2865.482999943197},{"type":"ms","text":3844.9899998959154},{"type":"bytes","text":0},{"type":"text","text":200},{"type":"text","text":"image/png"},{"type":"text","text":"image"}],[{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A42%3A19.478Z.png?alt=media&token=99f7a653-5780-411b-91c6-ca1a86b4a8a5"},{"type":"ms","text":2868.502999888733},{"type":"ms","text":3849.0140000358224},{"type":"bytes","text":0},{"type":"text","text":200},{"type":"text","text":"image/png"},{"type":"text","text":"image"}],[{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A32%3A53.884Z.png?alt=media&token=aca0478e-23b6-45d9-90d7-594641c37b77"},{"type":"ms","text":2871.157999848947},{"type":"ms","text":4056.5939999651164},{"type":"bytes","text":0},{"type":"text","text":200},{"type":"text","text":"image/png"},{"type":"text","text":"image"}],[{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A41%3A06.899Z.png?alt=media&token=ab32239e-a34f-4a94-880a-bc03dec7121b"},{"type":"ms","text":2906.4879999496043},{"type":"ms","text":4145.259999902919},{"type":"bytes","text":0},{"type":"text","text":200},{"type":"text","text":"image/png"},{"type":"text","text":"image"}],[{"type":"url","text":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu7GxKKTU1Kvnz.woff2"},{"type":"ms","text":2891.8200000189245},{"type":"ms","text":3592.509999871254},{"type":"bytes","text":8118},{"type":"text","text":200},{"type":"text","text":"font/woff2"},{"type":"text","text":"font"}],[{"type":"url","text":"chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/wrs_env.js"},{"type":"ms","text":3320.219999877736},{"type":"ms","text":3495.8009999245405},{"type":"bytes","text":0},{"type":"text","text":200},{"type":"text","text":"application/javascript"},{"type":"text","text":"script"}],[{"type":"url","text":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu7WxKKTU1Kvnz.woff2"},{"type":"ms","text":3632.0159998722374},{"type":"ms","text":4290.948000038043},{"type":"bytes","text":3375},{"type":"text","text":200},{"type":"text","text":"font/woff2"},{"type":"text","text":"font"}]]}},"score":100},{"id":"user-timings","weight":0,"group":"perf-info","result":{"score":true,"displayValue":"0","rawValue":true,"extendedInfo":{"value":[]},"scoringMode":"binary","informative":true,"name":"user-timings","description":"User Timing marks and measures","helpText":"Consider instrumenting your app with the User Timing API to create custom, real-world measurements of key user experiences. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/user-timing).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"text","text":"Name"},{"type":"text","itemType":"text","text":"Type"},{"type":"text","itemType":"text","text":"Time"}],"items":[]}},"score":100},{"id":"bootup-time","weight":0,"group":"perf-info","result":{"score":true,"displayValue":"750 ms","rawValue":746.6599998474121,"extendedInfo":{"value":{"chrome-extension://aapbdbdomjkkjkaonfhkkikfgjllcleb/bubble_compiled.js":{"Script Evaluation":102.56599998474121,"Script Parsing & Compile":89.31299996376038},"chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/ext/common.js":{"Script Evaluation":118.42399978637695,"Script Parsing & Compile":1.0329999923706055},"https://facebookfeed-neel.firebaseapp.com/":{"Parsing HTML & CSS":107.45000004768372},"https://facebookfeed-neel.firebaseapp.com/src/js/feed.js":{"Style & Layout":56.027000188827515,"Script Evaluation":6.446000099182129,"Script Parsing & Compile":5.7779998779296875},"chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/include.preload.js":{"Script Evaluation":40.31599998474121,"Script Parsing & Compile":10.980999946594238},"chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/content.js":{"Script Evaluation":46.75600028038025,"Script Parsing & Compile":1.0449998378753662},"https://facebookfeed-neel.firebaseapp.com/src/js/material.min.js":{"Style & Layout":28.432999849319458,"Script Evaluation":7.531000137329102,"Script Parsing & Compile":1.7829999923706055},"chrome-extension://fmkadmapgofadopljbjfkapdkoienihi/build/inject.js":{"Script Evaluation":7.674999952316284,"Script Parsing & Compile":7.582000017166138},"chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/notification.js":{"Script Parsing & Compile":7.745999813079834,"Script Evaluation":7.26800012588501},"chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/adblock-bandaids.js":{"Script Evaluation":9.022000074386597,"Script Parsing & Compile":4.226000070571899},"chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/wrs_env.js":{"Script Evaluation":11.585000038146973,"Script Parsing & Compile":1.5810000896453857,"Style & Layout":0.03399991989135742},"chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/browser-polyfill.js":{"Script Evaluation":6.94599986076355,"Script Parsing & Compile":5.55400013923645},"https://facebookfeed-neel.firebaseapp.com/src/js/idb.js":{"Script Evaluation":4.460999965667725,"Script Parsing & Compile":3.4110000133514404},"chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/adblock-picreplacement-contentscript-loader.js":{"Script Evaluation":6.164999961853027,"Script Parsing & Compile":0.5950000286102295},"https://facebookfeed-neel.firebaseapp.com/src/js/fetch.js":{"Script Parsing & Compile":6.11899995803833,"Script Evaluation":0.4419999122619629},"https://facebookfeed-neel.firebaseapp.com/src/js/promise.js":{"Script Parsing & Compile":4.788000106811523,"Script Evaluation":0.9969997406005859},"chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/elemHideEmulation.js":{"Script Parsing & Compile":5.049000024795532,"Script Evaluation":0.23399996757507324},"chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/adblock-functions.js":{"Script Parsing & Compile":2.628999948501587,"Script Evaluation":1.6170001029968262},"https://facebookfeed-neel.firebaseapp.com/src/js/utility.js":{"Script Evaluation":2.7930002212524414,"Script Parsing & Compile":1.2219998836517334},"https://facebookfeed-neel.firebaseapp.com/src/js/app.js":{"Script Evaluation":3.2070000171661377,"Script Parsing & Compile":0.565000057220459},"chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/ext/content.js":{"Script Evaluation":2.4630000591278076,"Script Parsing & Compile":0.6079998016357422},"chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/adblock-notificationoverlay.js":{"Script Parsing & Compile":2.2879998683929443,"Script Evaluation":0.42600011825561523},"chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/include.postload.js":{"Script Parsing & Compile":1.6110000610351562,"Script Evaluation":0.4119999408721924},"chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/adblock-uiscripts-rightclick_hook.js":{"Script Parsing & Compile":0.8050000667572021,"Script Evaluation":0.6310000419616699},"https://facebookfeed-neel.firebaseapp.com/sw.js":{"Parsing HTML & CSS":0.020999908447265625}}},"scoringMode":"binary","name":"bootup-time","description":"JavaScript boot-up time","helpText":"Consider reducing the time spent parsing, compiling, and executing JS. You may find delivering smaller JS payloads helps with this. [Learn more](https://developers.google.com/web/lighthouse/audits/bootup).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Script Evaluation"},{"type":"text","itemType":"text","text":"Script Parsing & Compile"}],"items":[[{"type":"url","text":"chrome-extension://aapbdbdomjkkjkaonfhkkikfgjllcleb/bubble_compiled.js"},{"type":"text","text":"103 ms"},{"type":"text","text":"89 ms"}],[{"type":"url","text":"chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/ext/common.js"},{"type":"text","text":"118 ms"},{"type":"text","text":"1 ms"}],[{"type":"url","text":"chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/include.preload.js"},{"type":"text","text":"40 ms"},{"type":"text","text":"11 ms"}],[{"type":"url","text":"chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/content.js"},{"type":"text","text":"47 ms"},{"type":"text","text":"1 ms"}],[{"type":"url","text":"chrome-extension://fmkadmapgofadopljbjfkapdkoienihi/build/inject.js"},{"type":"text","text":"8 ms"},{"type":"text","text":"8 ms"}],[{"type":"url","text":"chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/notification.js"},{"type":"text","text":"7 ms"},{"type":"text","text":"8 ms"}],[{"type":"url","text":"chrome-extension://gighmmpiobklfepjocnamgkkbiglidom/adblock-bandaids.js"},{"type":"text","text":"9 ms"},{"type":"text","text":"4 ms"}],[{"type":"url","text":"chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/wrs_env.js"},{"type":"text","text":"12 ms"},{"type":"text","text":"2 ms"}],[{"type":"url","text":"chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/browser-polyfill.js"},{"type":"text","text":"7 ms"},{"type":"text","text":"6 ms"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/src/js/feed.js"},{"type":"text","text":"6 ms"},{"type":"text","text":"6 ms"}]]}},"score":100},{"id":"screenshot-thumbnails","weight":0,"result":{"score":null,"displayValue":"","rawValue":null,"error":true,"debugString":"Audit error: Images have different sizes!","scoringMode":"binary","informative":true,"name":"screenshot-thumbnails","description":"Screenshot Thumbnails","helpText":"This is what the load of your site looked like."},"score":0},{"id":"mainthread-work-breakdown","weight":0,"group":"perf-info","result":{"score":true,"displayValue":"1,600 ms","rawValue":1596.9429988861084,"extendedInfo":{"value":{"Evaluate Script":449.4710006713867,"Recalculate Style":287.753999710083,"Compile Script":183.61499977111816,"Layout":152.54500007629395,"Parse HTML":107.49699997901917,"DOM GC":85.07699966430664,"Run Microtasks":79.31799960136414,"Minor GC":66.71499991416931,"Update Layer Tree":55.695000410079956,"Paint":41.459999561309814,"Parse Stylesheet":38.2039999961853,"Major GC":37.06899952888489,"Composite Layers":12.523000001907349}},"scoringMode":"binary","informative":true,"name":"mainthread-work-breakdown","description":"Main thread work breakdown","helpText":"Consider reducing the time spent parsing, compiling and executing JS.You may find delivering smaller JS payloads helps with this.","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"text","text":"Category"},{"type":"text","itemType":"text","text":"Work"},{"type":"text","itemType":"text","text":"Time spent"}],"items":[[{"type":"text","text":"Script Evaluation"},{"type":"text","text":"Evaluate Script"},{"type":"text","text":"449 ms"}],[{"type":"text","text":"Script Evaluation"},{"type":"text","text":"Run Microtasks"},{"type":"text","text":"79 ms"}],[{"type":"text","text":"Style & Layout"},{"type":"text","text":"Recalculate Style"},{"type":"text","text":"288 ms"}],[{"type":"text","text":"Style & Layout"},{"type":"text","text":"Layout"},{"type":"text","text":"153 ms"}],[{"type":"text","text":"Garbage collection"},{"type":"text","text":"DOM GC"},{"type":"text","text":"85 ms"}],[{"type":"text","text":"Garbage collection"},{"type":"text","text":"Minor GC"},{"type":"text","text":"67 ms"}],[{"type":"text","text":"Garbage collection"},{"type":"text","text":"Major GC"},{"type":"text","text":"37 ms"}],[{"type":"text","text":"Script Parsing & Compile"},{"type":"text","text":"Compile Script"},{"type":"text","text":"184 ms"}],[{"type":"text","text":"Parsing HTML & CSS"},{"type":"text","text":"Parse HTML"},{"type":"text","text":"107 ms"}],[{"type":"text","text":"Parsing HTML & CSS"},{"type":"text","text":"Parse Stylesheet"},{"type":"text","text":"38 ms"}],[{"type":"text","text":"Compositing"},{"type":"text","text":"Update Layer Tree"},{"type":"text","text":"56 ms"}],[{"type":"text","text":"Compositing"},{"type":"text","text":"Composite Layers"},{"type":"text","text":"13 ms"}],[{"type":"text","text":"Paint"},{"type":"text","text":"Paint"},{"type":"text","text":"41 ms"}]]}},"score":100},{"id":"font-display","weight":0,"group":"perf-info","result":{"score":true,"displayValue":"","rawValue":true,"scoringMode":"binary","name":"font-display","description":"All text remains visible during webfont loads","helpText":"Leverage the font-display CSS feature to ensure text is user-visible while webfonts are loading. [Learn more](https://developers.google.com/web/updates/2016/02/font-display).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"Font URL"},{"type":"text","itemType":"text","text":"Font download time"}],"items":[]}},"score":100}],"id":"performance","score":82.94117647058823},{"name":"Progressive Web App","weight":1,"description":"These checks validate the aspects of a Progressive Web App, as specified by the baseline [PWA Checklist](https://developers.google.com/web/progressive-web-apps/checklist).","audits":[{"id":"service-worker","weight":1,"result":{"score":true,"displayValue":"","rawValue":true,"scoringMode":"binary","name":"service-worker","description":"Registers a service worker","helpText":"The service worker is the technology that enables your app to use many Progressive Web App features, such as offline, add to homescreen, and push notifications. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/registered-service-worker)."},"score":100},{"id":"works-offline","weight":1,"result":{"score":true,"displayValue":"","rawValue":true,"scoringMode":"binary","name":"works-offline","description":"Responds with a 200 when offline","helpText":"If you're building a Progressive Web App, consider using a service worker so that your app can work offline. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/http-200-when-offline)."},"score":100},{"id":"without-javascript","weight":1,"result":{"score":true,"displayValue":"","rawValue":true,"scoringMode":"binary","name":"without-javascript","description":"Contains some content when JavaScript is not available","helpText":"Your app should display some content when JavaScript is disabled, even if it's just a warning to the user that JavaScript is required to use the app. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/no-js)."},"score":100},{"id":"is-on-https","weight":1,"result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"value":[]},"scoringMode":"binary","name":"is-on-https","description":"Uses HTTPS","helpText":"All sites should be protected with HTTPS, even ones that don't handle sensitive data. HTTPS prevents intruders from tampering with or passively listening in on the communications between your app and your users, and is a prerequisite for HTTP/2 and many new web platform APIs. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/https).","details":{"type":"list","header":{"type":"text","text":"Insecure URLs:"},"items":[]}},"score":100},{"id":"redirects-http","weight":1,"result":{"score":true,"displayValue":"","rawValue":true,"scoringMode":"binary","name":"redirects-http","description":"Redirects HTTP traffic to HTTPS","helpText":"If you've already set up HTTPS, make sure that you redirect all HTTP traffic to HTTPS. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/http-redirects-to-https)."},"score":100},{"id":"load-fast-enough-for-pwa","weight":1,"result":{"score":true,"displayValue":"","rawValue":true,"debugString":"First Interactive was found at 4,500 ms; however, the network request latencies were not sufficiently realistic, so the performance measurements cannot be trusted.","extendedInfo":{"value":{"areLatenciesAll3G":false,"firstRequestLatencies":[{"url":"https://facebookfeed-neel.firebaseapp.com/","latency":"564.35"},{"url":"https://fonts.googleapis.com/css?family=Roboto:400,700","latency":"571.17"},{"url":"https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css","latency":"583.66"},{"url":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu4mxKKTU1Kg.woff2","latency":"630.16"},{"url":"https://facebookfeed-neel.firebaseio.com/posts.json","latency":"585.11"},{"url":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c","latency":"0.2"},{"url":"chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/wrs_env.js","latency":"0.04"}],"isFast":true,"timeToFirstInteractive":4502.306}},"scoringMode":"binary","name":"load-fast-enough-for-pwa","description":"Page load is fast enough on 3G","helpText":"A fast page load over a 3G network ensures a good mobile user experience. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/fast-3g).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Latency (ms)"}],"items":[[{"type":"url","text":"https://facebookfeed-neel.firebaseapp.com/"},{"type":"text","text":"564.35"}],[{"type":"url","text":"https://fonts.googleapis.com/css?family=Roboto:400,700"},{"type":"text","text":"571.17"}],[{"type":"url","text":"https://cdnjs.cloudflare.com/ajax/libs/material-design-lite/1.3.0/material.indigo-pink.min.css"},{"type":"text","text":"583.66"}],[{"type":"url","text":"https://fonts.gstatic.com/s/roboto/v18/KFOmCnqEu92Fr1Mu4mxKKTU1Kg.woff2"},{"type":"text","text":"630.16"}],[{"type":"url","text":"https://facebookfeed-neel.firebaseio.com/posts.json"},{"type":"text","text":"585.11"}],[{"type":"url","text":"https://firebasestorage.googleapis.com/v0/b/facebookfeed-neel.appspot.com/o/2018-05-06T06%3A46%3A01.738Z.png?alt=media&token=4f08f0f2-3c5f-41ab-bdea-f8abe669f02c"},{"type":"text","text":"0.2"}],[{"type":"url","text":"chrome-extension://cmkdbmfndkfgebldhnkbfhlneefdaaip/js/wrs_env.js"},{"type":"text","text":"0.04"}]]}},"score":100},{"id":"webapp-install-banner","weight":1,"result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"value":{"warnings":[],"failures":[],"manifestValues":{"isParseFailure":false,"allChecks":[{"id":"hasStartUrl","failureText":"Manifest does not contain a `start_url`","passing":true},{"id":"hasIconsAtLeast192px","failureText":"Manifest does not have icons at least 192px","passing":true},{"id":"hasIconsAtLeast512px","failureText":"Manifest does not have icons at least 512px","passing":true},{"id":"hasPWADisplayValue","failureText":"Manifest's `display` value is not one of: minimal-ui | fullscreen | standalone","passing":true},{"id":"hasBackgroundColor","failureText":"Manifest does not have `background_color`","passing":true},{"id":"hasThemeColor","failureText":"Manifest does not have `theme_color`","passing":true},{"id":"hasShortName","failureText":"Manifest does not have `short_name`","passing":true},{"id":"shortNameLength","failureText":"Manifest `short_name` will be truncated when displayed on the homescreen","passing":true},{"id":"hasName","failureText":"Manifest does not have `name`","passing":true}]}}},"scoringMode":"binary","name":"webapp-install-banner","description":"User can be prompted to Install the Web App","helpText":"Browsers can proactively prompt users to add your app to their homescreen, which can lead to higher engagement. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/install-prompt)."},"score":100},{"id":"splash-screen","weight":1,"result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"value":{"failures":[],"manifestValues":{"isParseFailure":false,"allChecks":[{"id":"hasStartUrl","failureText":"Manifest does not contain a `start_url`","passing":true},{"id":"hasIconsAtLeast192px","failureText":"Manifest does not have icons at least 192px","passing":true},{"id":"hasIconsAtLeast512px","failureText":"Manifest does not have icons at least 512px","passing":true},{"id":"hasPWADisplayValue","failureText":"Manifest's `display` value is not one of: minimal-ui | fullscreen | standalone","passing":true},{"id":"hasBackgroundColor","failureText":"Manifest does not have `background_color`","passing":true},{"id":"hasThemeColor","failureText":"Manifest does not have `theme_color`","passing":true},{"id":"hasShortName","failureText":"Manifest does not have `short_name`","passing":true},{"id":"shortNameLength","failureText":"Manifest `short_name` will be truncated when displayed on the homescreen","passing":true},{"id":"hasName","failureText":"Manifest does not have `name`","passing":true}]}}},"scoringMode":"binary","name":"splash-screen","description":"Configured for a custom splash screen","helpText":"A themed splash screen ensures a high-quality experience when users launch your app from their homescreens. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/custom-splash-screen)."},"score":100},{"id":"themed-omnibox","weight":1,"result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"value":{"failures":[],"manifestValues":{"isParseFailure":false,"allChecks":[{"id":"hasStartUrl","failureText":"Manifest does not contain a `start_url`","passing":true},{"id":"hasIconsAtLeast192px","failureText":"Manifest does not have icons at least 192px","passing":true},{"id":"hasIconsAtLeast512px","failureText":"Manifest does not have icons at least 512px","passing":true},{"id":"hasPWADisplayValue","failureText":"Manifest's `display` value is not one of: minimal-ui | fullscreen | standalone","passing":true},{"id":"hasBackgroundColor","failureText":"Manifest does not have `background_color`","passing":true},{"id":"hasThemeColor","failureText":"Manifest does not have `theme_color`","passing":true},{"id":"hasShortName","failureText":"Manifest does not have `short_name`","passing":true},{"id":"shortNameLength","failureText":"Manifest `short_name` will be truncated when displayed on the homescreen","passing":true},{"id":"hasName","failureText":"Manifest does not have `name`","passing":true}]},"themeColor":"#3f51b5"}},"scoringMode":"binary","name":"themed-omnibox","description":"Address bar matches brand colors","helpText":"The browser address bar can be themed to match your site. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/address-bar)."},"score":100},{"id":"viewport","weight":1,"result":{"score":true,"displayValue":"","rawValue":true,"debugString":"","scoringMode":"binary","name":"viewport","description":"Has a `\u003cmeta name=\"viewport\">` tag with `width` or `initial-scale`","helpText":"Add a viewport meta tag to optimize your app for mobile screens. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/has-viewport-meta-tag)."},"score":100},{"id":"content-width","weight":1,"result":{"score":true,"displayValue":"","rawValue":true,"debugString":"","scoringMode":"binary","name":"content-width","description":"Content is sized correctly for the viewport","helpText":"If the width of your app's content doesn't match the width of the viewport, your app might not be optimized for mobile screens. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/content-sized-correctly-for-viewport)."},"score":100},{"id":"pwa-cross-browser","weight":0,"group":"manual-pwa-checks","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"pwa-cross-browser","description":"Site works cross-browser","helpText":"To reach the most number of users, sites should work across every major browser. [Learn more](https://developers.google.com/web/progressive-web-apps/checklist#site-works-cross-browser)."},"score":0},{"id":"pwa-page-transitions","weight":0,"group":"manual-pwa-checks","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"pwa-page-transitions","description":"Page transitions don't feel like they block on the network","helpText":"Transitions should feel snappy as you tap around, even on a slow network, a key to perceived performance. [Learn more](https://developers.google.com/web/progressive-web-apps/checklist#page-transitions-dont-feel-like-they-block-on-the-network)."},"score":0},{"id":"pwa-each-page-has-url","weight":0,"group":"manual-pwa-checks","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"pwa-each-page-has-url","description":"Each page has a URL","helpText":"Ensure individual pages are deep linkable via the URLs and that URLs are unique for the purpose of shareability on social media. [Learn more](https://developers.google.com/web/progressive-web-apps/checklist#each-page-has-a-url)."},"score":0}],"id":"pwa","score":100},{"name":"Accessibility","description":"These checks highlight opportunities to [improve the accessibility of your web app](https://developers.google.com/web/fundamentals/accessibility). Only a subset of accessibility issues can be automatically detected so manual testing is also encouraged.","audits":[{"id":"accesskeys","weight":0,"group":"a11y-correct-attributes","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"accesskeys","description":"`[accesskey]` values are not unique","helpText":"Access keys let users quickly focus a part of the page. For proper navigation, each access key must be unique. [Learn more](https://dequeuniversity.com/rules/axe/2.2/accesskeys?application=lighthouse)."},"score":100},{"id":"aria-allowed-attr","weight":3,"group":"a11y-aria","result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"aria-allowed-attr","description":"`[aria-*]` attributes match their roles","helpText":"Each ARIA `role` supports a specific subset of `aria-*` attributes. Mismatching these invalidates the `aria-*` attributes. [Learn more](https://dequeuniversity.com/rules/axe/2.2/aria-allowed-attr?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"score":100},{"id":"aria-required-attr","weight":2,"group":"a11y-aria","result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"aria-required-attr","description":"`[role]`s have all required `[aria-*]` attributes","helpText":"Some ARIA roles have required attributes that describe the state of the element to screen readers. [Learn more](https://dequeuniversity.com/rules/axe/2.2/aria-required-attr?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"score":100},{"id":"aria-required-children","weight":5,"group":"a11y-aria","result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"aria-required-children","description":"Elements with `[role]` that require specific children `[role]`s, are present","helpText":"Some ARIA parent roles must contain specific child roles to perform their intended accessibility functions. [Learn more](https://dequeuniversity.com/rules/axe/2.2/aria-required-children?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"score":100},{"id":"aria-required-parent","weight":2,"group":"a11y-aria","result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"aria-required-parent","description":"`[role]`s are contained by their required parent element","helpText":"Some ARIA child roles must be contained by specific parent roles to properly perform their intended accessibility functions. [Learn more](https://dequeuniversity.com/rules/axe/2.2/aria-required-parent?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"score":100},{"id":"aria-roles","weight":3,"group":"a11y-aria","result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"aria-roles","description":"`[role]` values are valid","helpText":"ARIA roles must have valid values in order to perform their intended accessibility functions. [Learn more](https://dequeuniversity.com/rules/axe/2.2/aria-roles?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"score":100},{"id":"aria-valid-attr-value","weight":2,"group":"a11y-aria","result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"aria-valid-attr-value","description":"`[aria-*]` attributes have valid values","helpText":"Assistive technologies, like screen readers, can't interpret ARIA attributes with invalid values. [Learn more](https://dequeuniversity.com/rules/axe/2.2/aria-valid-attr-value?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"score":100},{"id":"aria-valid-attr","weight":5,"group":"a11y-aria","result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"aria-valid-attr","description":"`[aria-*]` attributes are valid and not misspelled","helpText":"Assistive technologies, like screen readers, can't interpret ARIA attributes with invalid names. [Learn more](https://dequeuniversity.com/rules/axe/2.2/aria-valid-attr?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"score":100},{"id":"audio-caption","weight":0,"group":"a11y-correct-attributes","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"audio-caption","description":"`\u003caudio>` elements are missing a `\u003ctrack>` element with `[kind=\"captions\"]`.","helpText":"Captions make audio elements usable for deaf or hearing-impaired users, providing critical information such as who is talking, what they're saying, and other non-speech information. [Learn more](https://dequeuniversity.com/rules/axe/2.2/audio-caption?application=lighthouse)."},"score":100},{"id":"button-name","weight":10,"group":"a11y-element-names","result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"button-name","description":"Buttons have an accessible name","helpText":"When a button doesn't have an accessible name, screen readers announce it as \"button\", making it unusable for users who rely on screen readers. [Learn more](https://dequeuniversity.com/rules/axe/2.2/button-name?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"score":100},{"id":"bypass","weight":10,"group":"a11y-describe-contents","result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"bypass","description":"The page contains a heading, skip link, or landmark region","helpText":"Adding ways to bypass repetitive content lets keyboard users navigate the page more efficiently. [Learn more](https://dequeuniversity.com/rules/axe/2.2/bypass?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"score":100},{"id":"color-contrast","weight":6,"group":"a11y-color-contrast","result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"color-contrast","description":"Background and foreground colors have a sufficient contrast ratio","helpText":"Low-contrast text is difficult or impossible for many users to read. [Learn more](https://dequeuniversity.com/rules/axe/2.2/color-contrast?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"score":100},{"id":"definition-list","weight":0,"group":"a11y-well-structured","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"definition-list","description":"`\u003cdl>`'s do not contain only properly-ordered `\u003cdt>` and `\u003cdd>` groups, `\u003cscript>` or `\u003ctemplate>` elements.","helpText":"When definition lists are not properly marked up, screen readers may produce confusing or inaccurate output. [Learn more](https://dequeuniversity.com/rules/axe/2.2/definition-list?application=lighthouse)."},"score":100},{"id":"dlitem","weight":0,"group":"a11y-well-structured","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"dlitem","description":"Definition list items are not wrapped in `\u003cdl>` elements","helpText":"Definition list items (`\u003cdt>` and `\u003cdd>`) must be wrapped in a parent `\u003cdl>` element to ensure that screen readers can properly announce them. [Learn more](https://dequeuniversity.com/rules/axe/2.2/dlitem?application=lighthouse)."},"score":100},{"id":"document-title","weight":2,"group":"a11y-describe-contents","result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"document-title","description":"Document has a `\u003ctitle>` element","helpText":"The title gives screen reader users an overview of the page, and search engine users rely on it heavily to determine if a page is relevant to their search. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/title).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"score":100},{"id":"duplicate-id","weight":5,"group":"a11y-well-structured","result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"duplicate-id","description":"`[id]` attributes on the page are unique","helpText":"The value of an id attribute must be unique to prevent other instances from being overlooked by assistive technologies. [Learn more](https://dequeuniversity.com/rules/axe/2.2/duplicate-id?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"score":100},{"id":"frame-title","weight":0,"group":"a11y-describe-contents","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"frame-title","description":"`\u003cframe>` or `\u003ciframe>` elements do not have a title","helpText":"Screen reader users rely on frame titles to describe the contents of frames. [Learn more](https://dequeuniversity.com/rules/axe/2.2/frame-title?application=lighthouse)."},"score":100},{"id":"html-has-lang","weight":4,"group":"a11y-language","result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"html-has-lang","description":"`\u003chtml>` element has a `[lang]` attribute","helpText":"If a page doesn't specify a lang attribute, a screen reader assumes that the page is in the default language that the user chose when setting up the screen reader. If the page isn't actually in the default language, then the screen reader might not announce the page's text correctly. [Learn more](https://dequeuniversity.com/rules/axe/2.2/html-lang?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"score":100},{"id":"html-lang-valid","weight":1,"group":"a11y-language","result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"html-lang-valid","description":"`\u003chtml>` element has a valid value for its `[lang]` attribute","helpText":"Specifying a valid [BCP 47 language](https://www.w3.org/International/questions/qa-choosing-language-tags#question) helps screen readers announce text properly. [Learn more](https://dequeuniversity.com/rules/axe/2.2/valid-lang?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"score":100},{"id":"image-alt","weight":8,"group":"a11y-correct-attributes","result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"image-alt","description":"Image elements have `[alt]` attributes","helpText":"Informative elements should aim for short, descriptive alternate text. Decorative elements can be ignored with an empty alt attribute.[Learn more](https://dequeuniversity.com/rules/axe/2.2/image-alt?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"score":100},{"id":"input-image-alt","weight":0,"group":"a11y-correct-attributes","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"input-image-alt","description":"`\u003cinput type=\"image\">` elements do not have `[alt]` text","helpText":"When an image is being used as an `\u003cinput>` button, providing alternative text can help screen reader users understand the purpose of the button. [Learn more](https://dequeuniversity.com/rules/axe/2.2/input-image-alt?application=lighthouse)."},"score":100},{"id":"label","weight":10,"group":"a11y-describe-contents","result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"label","description":"Form elements have associated labels","helpText":"Labels ensure that form controls are announced properly by assistive technologies, like screen readers. [Learn more](https://dequeuniversity.com/rules/axe/2.2/label?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"score":100},{"id":"layout-table","weight":0,"group":"a11y-describe-contents","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"layout-table","description":"Presentational `\u003ctable>` elements do not avoid using `\u003cth>`, `\u003ccaption>` or the `[summary]` attribute.","helpText":"A table being used for layout purposes should not include data elements, such as the th or caption elements or the summary attribute, because this can create a confusing experience for screen reader users. [Learn more](https://dequeuniversity.com/rules/axe/2.2/layout-table?application=lighthouse)."},"score":100},{"id":"link-name","weight":0,"group":"a11y-element-names","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"link-name","description":"Links do not have a discernible name","helpText":"Link text (and alternate text for images, when used as links) that is discernible, unique, and focusable improves the navigation experience for screen reader users. [Learn more](https://dequeuniversity.com/rules/axe/2.2/link-name?application=lighthouse)."},"score":100},{"id":"list","weight":0,"group":"a11y-well-structured","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"list","description":"Lists do not contain only `\u003cli>` elements and script supporting elements (`\u003cscript>` and `\u003ctemplate>`).","helpText":"Screen readers have a specific way of announcing lists. Ensuring proper list structure aids screen reader output. [Learn more](https://dequeuniversity.com/rules/axe/2.2/list?application=lighthouse)."},"score":100},{"id":"listitem","weight":0,"group":"a11y-well-structured","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"listitem","description":"List items (`\u003cli>`) are not contained within `\u003cul>` or `\u003col>` parent elements.","helpText":"Screen readers require list items (`\u003cli>`) to be contained within a parent `\u003cul>` or `\u003col>` to be announced properly. [Learn more](https://dequeuniversity.com/rules/axe/2.2/listitem?application=lighthouse)."},"score":100},{"id":"meta-refresh","weight":0,"group":"a11y-meta","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"meta-refresh","description":"The document uses `\u003cmeta http-equiv=\"refresh\">`","helpText":"Users do not expect a page to refresh automatically, and doing so will move focus back to the top of the page. This may create a frustrating or confusing experience. [Learn more](https://dequeuniversity.com/rules/axe/2.2/meta-refresh?application=lighthouse)."},"score":100},{"id":"meta-viewport","weight":3,"group":"a11y-meta","result":{"score":false,"displayValue":"","rawValue":false,"extendedInfo":{"value":{"description":"Ensures \u003cmeta name=\"viewport\"> does not disable text scaling and zooming","help":"Zooming and scaling must not be disabled","helpUrl":"https://dequeuniversity.com/rules/axe/3.0/meta-viewport?application=axeAPI","id":"meta-viewport","impact":"critical","nodes":[{"failureSummary":"Fix any of the following:\n  \u003cmeta> tag disables zooming on mobile devices","html":"\u003cmeta name=\"viewport\" content=\"width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0\">","impact":"critical","path":"1,HTML,0,HEAD,1,META","snippet":"\u003cmeta name=\"viewport\" content=\"width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0\">","target":["meta[name=\"viewport\"]"]}],"tags":["cat.sensory-and-visual-cues","wcag2aa","wcag144"]}},"scoringMode":"binary","name":"meta-viewport","description":"`[user-scalable=\"no\"]` is used in the `\u003cmeta name=\"viewport\">` element or the `[maximum-scale]` attribute is less than 5.","helpText":"Disabling zooming is problematic for users with low vision who rely on screen magnification to properly see the contents of a web page. [Learn more](https://dequeuniversity.com/rules/axe/2.2/meta-viewport?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[{"type":"node","selector":"meta[name=\"viewport\"]","path":"1,HTML,0,HEAD,1,META","snippet":"\u003cmeta name=\"viewport\" content=\"width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0\">"}]}},"score":0},{"id":"object-alt","weight":0,"group":"a11y-describe-contents","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"object-alt","description":"`\u003cobject>` elements do not have `[alt]` text","helpText":"Screen readers cannot translate non-text content. Adding alt text to `\u003cobject>` elements helps screen readers convey meaning to users. [Learn more](https://dequeuniversity.com/rules/axe/2.2/object-alt?application=lighthouse)."},"score":100},{"id":"tabindex","weight":4,"group":"a11y-correct-attributes","result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"tabindex","description":"No element has a `[tabindex]` value greater than 0","helpText":"A value greater than 0 implies an explicit navigation ordering. Although technically valid, this often creates frustrating experiences for users who rely on assistive technologies. [Learn more](https://dequeuniversity.com/rules/axe/2.2/tabindex?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"score":100},{"id":"td-headers-attr","weight":0,"group":"a11y-correct-attributes","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"td-headers-attr","description":"Cells in a `\u003ctable>` element that use the `[headers]` attribute refers to other cells of that same table.","helpText":"Screen readers have features to make navigating tables easier. Ensuring `\u003ctd>` cells using the `[headers]` attribute only refer to other cells in the same table may improve the experience for screen reader users. [Learn more](https://dequeuniversity.com/rules/axe/2.2/td-headers-attr?application=lighthouse)."},"score":100},{"id":"th-has-data-cells","weight":0,"group":"a11y-correct-attributes","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"th-has-data-cells","description":"`\u003cth>` elements and elements with `[role=\"columnheader\"/\"rowheader\"]` do not have data cells they describe.","helpText":"Screen readers have features to make navigating tables easier. Ensuring table headers always refer to some set of cells may improve the experience for screen reader users. [Learn more](https://dequeuniversity.com/rules/axe/2.2/th-has-data-cells?application=lighthouse)."},"score":100},{"id":"valid-lang","weight":0,"group":"a11y-language","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"valid-lang","description":"`[lang]` attributes do not have a valid value","helpText":"Specifying a valid [BCP 47 language](https://www.w3.org/International/questions/qa-choosing-language-tags#question) on elements helps ensure that text is pronounced correctly by a screen reader. [Learn more](https://dequeuniversity.com/rules/axe/2.2/valid-lang?application=lighthouse)."},"score":100},{"id":"video-caption","weight":4,"group":"a11y-describe-contents","result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"video-caption","description":"`\u003cvideo>` elements contain a `\u003ctrack>` element with `[kind=\"captions\"]`","helpText":"When a video provides a caption it is easier for deaf and hearing impaired users to access its information. [Learn more](https://dequeuniversity.com/rules/axe/2.2/video-caption?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"score":100},{"id":"video-description","weight":3,"group":"a11y-describe-contents","result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"video-description","description":"`\u003cvideo>` elements contain a `\u003ctrack>` element with `[kind=\"description\"]`","helpText":"Audio descriptions provide relevant information for videos that dialogue cannot, such as facial expressions and scenes. [Learn more](https://dequeuniversity.com/rules/axe/2.2/video-description?application=lighthouse).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"score":100},{"id":"logical-tab-order","weight":0,"group":"manual-a11y-checks","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"logical-tab-order","description":"The page has a logical tab order","helpText":"Tabbing through the page follows the visual layout. Users cannot focus elements that are offscreen. [Learn more](https://developers.google.com/web/fundamentals/accessibility/how-to-review#start_with_the_keyboard)."},"score":0},{"id":"focusable-controls","weight":0,"group":"manual-a11y-checks","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"focusable-controls","description":"Interactive controls are keyboard focusable","helpText":"Custom interactive controls are keyboard focusable and display a focus indicator. [Learn more](https://developers.google.com/web/fundamentals/accessibility/how-to-review#start_with_the_keyboard)."},"score":0},{"id":"managed-focus","weight":0,"group":"manual-a11y-checks","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"managed-focus","description":"The user's focus is directed to new content added to the page","helpText":"If new content, such as a dialog, is added to the page, the user's focus is directed to it. [Learn more](https://developers.google.com/web/fundamentals/accessibility/how-to-review#start_with_the_keyboard)."},"score":0},{"id":"focus-traps","weight":0,"group":"manual-a11y-checks","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"focus-traps","description":"User focus is not accidentally trapped in a region","helpText":"A user can tab into and out of any control or region without accidentally trapping their focus. [Learn more](https://developers.google.com/web/fundamentals/accessibility/how-to-review#start_with_the_keyboard)."},"score":0},{"id":"custom-controls-labels","weight":0,"group":"manual-a11y-checks","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"custom-controls-labels","description":"Custom controls have associated labels","helpText":"Custom interactive controls have associated labels, provided by aria-label or aria-labelledby. [Learn more](https://developers.google.com/web/fundamentals/accessibility/how-to-review#try_it_with_a_screen_reader)."},"score":0},{"id":"custom-controls-roles","weight":0,"group":"manual-a11y-checks","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"custom-controls-roles","description":"Custom controls have ARIA roles","helpText":"Custom interactive controls have appropriate ARIA roles. [Learn more](https://developers.google.com/web/fundamentals/accessibility/how-to-review#try_it_with_a_screen_reader)."},"score":0},{"id":"visual-order-follows-dom","weight":0,"group":"manual-a11y-checks","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"visual-order-follows-dom","description":"Visual order on the page follows DOM order","helpText":"DOM order matches the visual order, improving navigation for assistive technology. [Learn more](https://developers.google.com/web/fundamentals/accessibility/how-to-review#try_it_with_a_screen_reader)."},"score":0},{"id":"offscreen-content-hidden","weight":0,"group":"manual-a11y-checks","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"offscreen-content-hidden","description":"Offscreen content is hidden from assistive technology","helpText":"Offscreen content is hidden with display: none or aria-hidden=true. [Learn more](https://developers.google.com/web/fundamentals/accessibility/how-to-review#try_it_with_a_screen_reader)."},"score":0},{"id":"heading-levels","weight":0,"group":"manual-a11y-checks","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"heading-levels","description":"Headings don't skip levels","helpText":"Headings are used to create an outline for the page and heading levels are not skipped. [Learn more](https://developers.google.com/web/fundamentals/accessibility/how-to-review#take_advantage_of_headings_and_landmarks)."},"score":0},{"id":"use-landmarks","weight":0,"group":"manual-a11y-checks","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"use-landmarks","description":"HTML5 landmark elements are used to improve navigation","helpText":"Landmark elements (\u003cmain>, \u003cnav>, etc.) are used to improve the keyboard navigation of the page for assistive technology. [Learn more](https://developers.google.com/web/fundamentals/accessibility/how-to-review#take_advantage_of_headings_and_landmarks)."},"score":0}],"id":"accessibility","score":96.73913043478261},{"name":"Best Practices","description":"We've compiled some recommendations for modernizing your web app and avoiding performance pitfalls.","audits":[{"id":"appcache-manifest","weight":1,"result":{"score":true,"displayValue":"","rawValue":true,"debugString":"","scoringMode":"binary","name":"appcache-manifest","description":"Avoids Application Cache","helpText":"Application Cache is deprecated. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/appcache)."},"score":100},{"id":"no-websql","weight":1,"result":{"score":true,"displayValue":"","rawValue":true,"debugString":"","scoringMode":"binary","name":"no-websql","description":"Avoids WebSQL DB","helpText":"Web SQL is deprecated. Consider using IndexedDB instead. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/web-sql)."},"score":100},{"id":"is-on-https","weight":1,"result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"value":[]},"scoringMode":"binary","name":"is-on-https","description":"Uses HTTPS","helpText":"All sites should be protected with HTTPS, even ones that don't handle sensitive data. HTTPS prevents intruders from tampering with or passively listening in on the communications between your app and your users, and is a prerequisite for HTTP/2 and many new web platform APIs. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/https).","details":{"type":"list","header":{"type":"text","text":"Insecure URLs:"},"items":[]}},"score":100},{"id":"uses-http2","weight":1,"result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"value":{"results":[]}},"scoringMode":"binary","name":"uses-http2","description":"Uses HTTP/2 for its own resources","helpText":"HTTP/2 offers many benefits over HTTP/1.1, including binary headers, multiplexing, and server push. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/http2).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Protocol"}],"items":[]}},"score":100},{"id":"uses-passive-event-listeners","weight":1,"result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"value":[]},"scoringMode":"binary","name":"uses-passive-event-listeners","description":"Uses passive listeners to improve scrolling performance","helpText":"Consider marking your touch and wheel event listeners as `passive` to improve your page's scroll performance. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/passive-event-listeners).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Location"}],"items":[]}},"score":100},{"id":"no-mutation-events","weight":1,"result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"value":{"results":[]}},"scoringMode":"binary","name":"no-mutation-events","description":"Avoids Mutation Events in its own scripts","helpText":"Mutation Events are deprecated and harm performance. Consider using Mutation Observers instead. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/mutation-events).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"code","text":"Event"},{"type":"text","itemType":"text","text":"Line"},{"type":"text","itemType":"text","text":"Col"},{"type":"text","itemType":"code","text":"Snippet"}],"items":[]}},"score":100},{"id":"no-document-write","weight":1,"result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"value":[]},"scoringMode":"binary","name":"no-document-write","description":"Avoids `document.write()`","helpText":"For users on slow connections, external scripts dynamically injected via `document.write()` can delay page load by tens of seconds. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/document-write).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Location"}],"items":[]}},"score":100},{"id":"external-anchors-use-rel-noopener","weight":1,"result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"value":[]},"scoringMode":"binary","name":"external-anchors-use-rel-noopener","description":"Opens external anchors using `rel=\"noopener\"`","helpText":"Open new tabs using `rel=\"noopener\"` to improve performance and prevent security vulnerabilities. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/noopener).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Target"},{"type":"text","itemType":"text","text":"Rel"}],"items":[]}},"score":100},{"id":"geolocation-on-start","weight":1,"result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"value":[]},"scoringMode":"binary","name":"geolocation-on-start","description":"Avoids requesting the geolocation permission on page load","helpText":"Users are mistrustful of or confused by sites that request their location without context. Consider tying the request to user gestures instead. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/geolocation-on-load).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Location"}],"items":[]}},"score":100},{"id":"no-vulnerable-libraries","weight":1,"result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"jsLibs":[{"name":"Material Design Lite","npmPkgName":"material-design-lite","version":null,"vulns":[]}],"vulnerabilities":[]},"scoringMode":"binary","name":"no-vulnerable-libraries","description":"Avoids front-end JavaScript libraries with known security vulnerabilities","helpText":"Some third-party scripts may contain known security vulnerabilities  that are easily identified and exploited by attackers.","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"link","text":"Library Version"},{"type":"text","itemType":"text","text":"Vulnerability Count"},{"type":"text","itemType":"text","text":"Highest Severity"}],"items":[]}},"score":100},{"id":"notification-on-start","weight":1,"result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"value":[]},"scoringMode":"binary","name":"notification-on-start","description":"Avoids requesting the notification permission on page load","helpText":"Users are mistrustful of or confused by sites that request to send notifications without context. Consider tying the request to user gestures instead. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/notifications-on-load).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Location"}],"items":[]}},"score":100},{"id":"deprecations","weight":1,"result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"value":[]},"scoringMode":"binary","name":"deprecations","description":"Avoids deprecated APIs","helpText":"Deprecated APIs will eventually be removed from the browser. [Learn more](https://www.chromestatus.com/features#deprecated).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"code","text":"Deprecation / Warning"},{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Line"}],"items":[]}},"score":100},{"id":"manifest-short-name-length","weight":1,"result":{"score":true,"displayValue":"","rawValue":true,"scoringMode":"binary","name":"manifest-short-name-length","description":"Manifest's `short_name` won't be truncated when displayed on homescreen","helpText":"Make your app's `short_name` fewer than 12 characters to ensure that it's not truncated on homescreens. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/manifest-short_name-is-not-truncated)."},"score":100},{"id":"password-inputs-can-be-pasted-into","weight":1,"result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{"value":[]},"scoringMode":"binary","name":"password-inputs-can-be-pasted-into","description":"Allows users to paste into password fields","helpText":"Preventing password pasting undermines good security policy. [Learn more](https://www.ncsc.gov.uk/blog-post/let-them-paste-passwords)","details":{"type":"list","header":{"type":"text","text":"Password inputs that prevent pasting into"},"items":[]}},"score":100},{"id":"errors-in-console","weight":1,"result":{"score":true,"displayValue":"","rawValue":0,"scoringMode":"binary","name":"errors-in-console","description":"No browser errors logged to the console","helpText":"Errors logged to the console indicate unresolved problems. They can come from network request failures and other browser concerns.","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"code","text":"Description"}],"items":[]}},"score":100},{"id":"image-aspect-ratio","weight":1,"result":{"score":true,"displayValue":"","rawValue":true,"scoringMode":"binary","name":"image-aspect-ratio","description":"Displays images with correct aspect ratio","helpText":"Image display dimensions should match natural aspect ratio.","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"thumbnail","text":""},{"type":"text","itemType":"url","text":"URL"},{"type":"text","itemType":"text","text":"Aspect Ratio (Displayed)"},{"type":"text","itemType":"text","text":"Aspect Ratio (Actual)"}],"items":[]}},"score":100}],"id":"best-practices","score":100},{"name":"SEO","description":"These checks ensure that your page is optimized for search engine results ranking. There are additional factors Lighthouse does not check that may affect your search ranking. [Learn more](https://support.google.com/webmasters/answer/35769).","audits":[{"id":"viewport","weight":1,"group":"seo-mobile","result":{"score":true,"displayValue":"","rawValue":true,"debugString":"","scoringMode":"binary","name":"viewport","description":"Has a `\u003cmeta name=\"viewport\">` tag with `width` or `initial-scale`","helpText":"Add a viewport meta tag to optimize your app for mobile screens. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/has-viewport-meta-tag)."},"score":100},{"id":"document-title","weight":1,"group":"seo-content","result":{"score":true,"displayValue":"","rawValue":true,"extendedInfo":{},"scoringMode":"binary","name":"document-title","description":"Document has a `\u003ctitle>` element","helpText":"The title gives screen reader users an overview of the page, and search engine users rely on it heavily to determine if a page is relevant to their search. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/title).","details":{"type":"list","header":{"type":"text","text":"View failing elements"},"items":[]}},"score":100},{"id":"meta-description","weight":1,"group":"seo-content","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","name":"meta-description","description":"Document does not have a meta description","helpText":"Meta descriptions may be included in search results to concisely summarize page content. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/description)."},"score":0},{"id":"http-status-code","weight":1,"group":"seo-crawl","result":{"score":true,"displayValue":"","rawValue":true,"scoringMode":"binary","name":"http-status-code","description":"Page has successful HTTP status code","helpText":"Pages with unsuccessful HTTP status codes may not be indexed properly. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/successful-http-code)."},"score":100},{"id":"link-text","weight":1,"group":"seo-content","result":{"score":true,"displayValue":"","rawValue":true,"scoringMode":"binary","name":"link-text","description":"Links have descriptive text","helpText":"Descriptive link text helps search engines understand your content. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/descriptive-link-text).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"Link destination"},{"type":"text","itemType":"text","text":"Link Text"}],"items":[]}},"score":100},{"id":"is-crawlable","weight":1,"group":"seo-crawl","result":{"score":true,"displayValue":"","rawValue":true,"scoringMode":"binary","name":"is-crawlable","description":"Page isn’t blocked from indexing","helpText":"Search engines are unable to include your pages in search results if they don't have permission to crawl them. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/indexing).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"code","text":"Blocking Directive Source"}],"items":[]}},"score":100},{"id":"hreflang","weight":1,"group":"seo-content","result":{"score":true,"displayValue":"","rawValue":true,"scoringMode":"binary","name":"hreflang","description":"Document has a valid `hreflang`","helpText":"hreflang allows crawlers to discover alternate translations of the page content. [Learn more](https://support.google.com/webmasters/answer/189077).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"code","text":"Source"}],"items":[]}},"score":100},{"id":"canonical","weight":0,"group":"seo-content","result":{"score":true,"displayValue":"","rawValue":true,"scoringMode":"binary","informative":true,"notApplicable":true,"name":"canonical","description":"Document has a valid `rel=canonical`","helpText":"Canonical links suggest which URL to show in search results. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/canonical)."},"score":100},{"id":"font-size","weight":1,"group":"seo-mobile","result":{"score":true,"displayValue":"","rawValue":true,"debugString":null,"scoringMode":"binary","name":"font-size","description":"Document uses legible font sizes","helpText":"Font sizes less than 12px are too small to be legible and require mobile visitors to “pinch to zoom” in order to read. Strive to have >60% of page text ≥12px. [Learn more](https://developers.google.com/web/tools/lighthouse/audits/font-sizes).","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"url","text":"Source"},{"type":"text","itemType":"code","text":"Selector"},{"type":"text","itemType":"text","text":"% of Page Text"},{"type":"text","itemType":"text","text":"Font Size"}],"items":[[{"type":"url","text":"Legible text"},{"type":"code","text":null},{"type":"text","text":"100.00%"},{"type":"text","text":"≥ 12px"}]]}},"score":100},{"id":"plugins","weight":1,"group":"seo-content","result":{"score":true,"displayValue":"","rawValue":true,"scoringMode":"binary","name":"plugins","description":"Document avoids plugins","helpText":"Most mobile devices do not support plugins, and many desktop browsers restrict them.","details":{"type":"table","header":"View Details","itemHeaders":[{"type":"text","itemType":"code","text":"Element source"}],"items":[]}},"score":100},{"id":"mobile-friendly","weight":0,"group":"manual-seo-checks","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"mobile-friendly","description":"Page is mobile friendly","helpText":"Take the [Mobile-Friendly Test](https://search.google.com/test/mobile-friendly) to check for audits not covered by Lighthouse, like sizing tap targets appropriately. [Learn more](https://developers.google.com/search/mobile-sites/)."},"score":0},{"id":"structured-data","weight":0,"group":"manual-seo-checks","result":{"score":false,"displayValue":"","rawValue":false,"scoringMode":"binary","informative":true,"manual":true,"name":"structured-data","description":"Structured data is valid","helpText":"Run the [Structured Data Testing Tool](https://search.google.com/structured-data/testing-tool/) and the [Structured Data Linter](http://linter.structured-data.org/) to validate structured data. [Learn more](https://developers.google.com/search/docs/guides/mark-up-content)."},"score":0}],"id":"seo","score":88.88888888888889}],"reportGroups":{"perf-metric":{"title":"Metrics","description":"These metrics encapsulate your web app's performance across a number of dimensions."},"perf-hint":{"title":"Opportunities","description":"These are opportunities to speed up your application by optimizing the following resources."},"perf-info":{"title":"Diagnostics","description":"More information about the performance of your application."},"a11y-color-contrast":{"title":"Color Contrast Is Satisfactory","description":"These are opportunities to improve the legibility of your content."},"a11y-describe-contents":{"title":"Elements Describe Contents Well","description":"These are opportunities to make your content easier to understand for a user of assistive technology, like a screen reader."},"a11y-well-structured":{"title":"Elements Are Well Structured","description":"These are opportunities to make sure your HTML is appropriately structured."},"a11y-aria":{"title":"ARIA Attributes Follow Best Practices","description":"These are opportunities to improve the usage of ARIA in your application which may enhance the experience for users of assistive technology, like a screen reader."},"a11y-correct-attributes":{"title":"Elements Use Attributes Correctly","description":"These are opportunities to improve the configuration of your HTML elements."},"a11y-element-names":{"title":"Elements Have Discernible Names","description":"These are opportunities to improve the semantics of the controls in your application. This may enhance the experience for users of assistive technology, like a screen reader."},"a11y-language":{"title":"Page Specifies Valid Language","description":"These are opportunities to improve the interpretation of your content by users in different locales."},"a11y-meta":{"title":"Meta Tags Used Properly","description":"These are opportunities to improve the user experience of your site."},"manual-a11y-checks":{"title":"Additional items to manually check","description":"These items address areas which an automated testing tool cannot cover. Learn more in our guide on [conducting an accessibility review](https://developers.google.com/web/fundamentals/accessibility/how-to-review)."},"manual-pwa-checks":{"title":"Additional items to manually check","description":"These checks are required by the baseline [PWA Checklist](https://developers.google.com/web/progressive-web-apps/checklist) but are not automatically checked by Lighthouse. They do not affect your score but it's important that you verify them manually."},"seo-mobile":{"title":"Mobile Friendly","description":"Make sure your pages are mobile friendly so users don’t have to pinch or zoom in order to read the content pages. [Learn more](https://developers.google.com/search/mobile-sites/)."},"seo-content":{"title":"Content Best Practices","description":"Format your HTML in a way that enables crawlers to better understand your app’s content."},"seo-crawl":{"title":"Crawling and Indexing","description":"To appear in search results, crawlers need access to your app."},"manual-seo-checks":{"title":"Additional items to manually check","description":"Run these additional validators on your site to check additional SEO best practices."}}};</script>
  <script>
    window.addEventListener('DOMContentLoaded', _ => {
      const dom = new DOM(document);
      const renderer = new ReportRenderer(dom);

      const container = document.querySelector('main');
      renderer.renderReport(window.__LIGHTHOUSE_JSON__, container);

      // Hook in JS features and page-level event listeners after the report
      // is in the document.
      const features = new ReportUIFeatures(dom);
      features.initFeatures(window.__LIGHTHOUSE_JSON__);
    });

    document.addEventListener('lh-analytics', e => {
      if (window.ga) {
        ga(e.detail.cmd, e.detail.fields);
      }
    });

    document.addEventListener('lh-log', e => {
      const logger = new Logger(document.querySelector('#lh-log'));

      switch (e.detail.cmd) {
        case 'log':
          logger.log(e.detail.msg);
          break;
        case 'warn':
          logger.warn(e.detail.msg);
          break;
        case 'error':
          logger.error(e.detail.msg);
          break;
        case 'hide':
          logger.hide();
          break;
      }
    });
  </script>


</body></html>

##Features:
- Adding app to the home screen of the device.  
- Web-push notification on new feeds
- Background Sync  
- Caching Strategies for the offline support
https://facebookfeed-neel.firebaseapp.com/
