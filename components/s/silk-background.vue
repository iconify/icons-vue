<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="r5w9xt3ed"/><path clip-rule="evenodd" class="c7-a8wlue"/><path clip-rule="evenodd" class="c37x36-po"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:silk-background" /></template>
<style>
.c37x36-po {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M17.339 15.796a6.4 6.4 0 0 0 1.161-2.807a1.05 1.05 0 0 1-.701-.989a1.05 1.05 0 0 1 .701-.988a6.4 6.4 0 0 0-1.225-2.893q-.198.088-.431.09c-.587 0-1.064-.47-1.064-1.051c0-.143.03-.285.087-.416A6.6 6.6 0 0 0 12 5.5a6.6 6.6 0 0 0-3.895 1.263q.076.184.077.395c0 .58-.476 1.051-1.064 1.051q-.215-.001-.402-.077A6.4 6.4 0 0 0 5.5 11.028c.385.159.656.534.656.972a1.05 1.05 0 0 1-.656.972a6.4 6.4 0 0 0 1.157 2.814c.143-.071.305-.11.476-.11c.587 0 1.064.47 1.064 1.05c0 .177-.044.343-.122.489a6.6 6.6 0 0 0 3.926 1.285a6.6 6.6 0 0 0 3.908-1.272a1.04 1.04 0 0 1-.129-.502c0-.58.477-1.05 1.064-1.05c.172-.001.342.04.495.12m-4.144-4.21c.285-.347.844-1.233.803-1.987c-.052-.942-.62-1.993-2.023-3.1C11.285 7.027 10 8.202 10 9.6c0 1.16.485 1.674.758 1.964l.023.024l1.634 1.647c.158.166.468.624.438 1.13c-.036.632-.487 1.215-.853 1.531c-.289-.162-.873-.695-.902-1.531c-.02-.207.043-.734.463-1.191l-.78-.79c-.26.226-.78.94-.78 1.98c0 1.302 1.011 2.274 1.999 3.137c.665-.519 1.998-1.872 1.998-3.136s-.91-2.22-1.364-2.54l-1.073-1.034c-.154-.126-.463-.54-.463-1.19c0-.652.585-1.301.878-1.544c.292.226.877.853.877 1.543s-.292 1.082-.438 1.191z");
}

.c7-a8wlue {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M20 12a8 8 0 1 1-16 0a8 8 0 0 1 16 0m-.5 0a7.5 7.5 0 1 1-15 0a7.5 7.5 0 0 1 15 0");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r5w9xt3ed {
  fill: var(--svg-color--39c, #39c);
  d: path("M24 0H0v24h24z");
}

</style>
