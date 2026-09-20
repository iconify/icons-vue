<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="bb3gmxbva"/><path class="mfb9etb-x"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nexis-background" /></template>
<style>
.bb3gmxbva {
  fill: var(--svg-color--c5fe4a, #c5fe4a);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.mfb9etb-x {
  fill: var(--svg-color--000, #000);
  d: path("m6.53 17.835l.044.043l.56-.796c.464-.912.644-1.745.65-2.454a4.8 4.8 0 0 0-.156-1.12a4.4 4.4 0 0 1-.149-.674v-.01a5 5 0 0 1-.042-.463c-.098-2.513 1.855-4.665 4.36-4.807l-.018-.016c.597-.037 1.467.094 2.197-.098a4.4 4.4 0 0 0 1.99-1.204a.5.5 0 0 1 .088-.075l.514-.728a8 8 0 0 0-7.594-.836a7.996 7.996 0 0 0-4.378 10.428a8 8 0 0 0 1.932 2.81zM16.944 6.817a.6.6 0 0 1-.048.111c-.484.906-.69 2.274-.645 2.814c.072.898.347 1.481.262 2.169c.064 2.492-1.885 4.61-4.37 4.746h-.006c-.548.035-.611-.018-1.113.005c-1.034.046-2.138.479-2.904 1.287l-.512.728q.22.145.447.282l.207.113a7.999 7.999 0 0 0 9.169-12.946z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
