<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="d1zlf9gtx"/><path class="sx-zb3b9a"/><path class="ozopvgbup"/><path class="rmwy12b_c"/><path class="f3qgl8oyv"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:map-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.d1zlf9gtx {
  stroke: var(--svg-color--e1ca7d, #e1ca7d);
  d: path("M10.386 5.75c.717-1.242 2.51-1.242 3.227 0l6.135 10.64c.716 1.241-.18 2.793-1.614 2.793H5.865c-1.433 0-2.33-1.552-1.613-2.793z");
}

.f3qgl8oyv {
  stroke: var(--svg-color--e1ca7d, #e1ca7d);
  d: path("M12.913 10.738a.534.534 0 0 1 .743.124a.53.53 0 0 1 .096.259l.472 4.95a.532.532 0 0 1-.751.534l-4.52-2.062a.532.532 0 0 1-.088-.917z");
}

.ft5dv1b6b {
  fill: none;
}

.ozopvgbup {
  stroke: var(--svg-color--e1ca7d, #e1ca7d);
  d: path("M11.893 8.441a1.33 1.33 0 0 1 2.266.42l2.617 7.403a1.33 1.33 0 0 1-1.496 1.752l-7.713-1.43a1.33 1.33 0 0 1-.77-2.17z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rmwy12b_c {
  stroke: var(--svg-color--e1ca7d, #e1ca7d);
  d: path("M12.597 9.413a.798.798 0 0 1 1.329.382l1.644 6.632a.8.8 0 0 1-.995.96l-6.56-1.888a.8.8 0 0 1-.334-1.34z");
}

.sx-zb3b9a {
  stroke: var(--svg-color--e1ca7d, #e1ca7d);
  d: path("M11.032 7.48c.825-1.173 2.613-1.012 3.214.29l3.813 8.246c.601 1.3-.43 2.765-1.858 2.636l-9.038-.815c-1.428-.128-2.181-1.754-1.357-2.926z");
}

</style>
