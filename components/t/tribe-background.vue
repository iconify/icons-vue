<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ol-o90bcc"/><path class="e951knbfu"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tribe-background" /></template>
<style>
.e951knbfu {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.414 4.668c-.268.314-.268.754-.268 1.628s0 1.308.268 1.623l.115.114c.308.274.754.308 1.645.371c3.214.224 6.44.224 9.653 0c.892-.063 1.337-.097 1.646-.371l.114-.114c.268-.315.268-.749.268-1.628c0-.874 0-1.314-.268-1.628a1 1 0 0 0-.114-.115c-.314-.274-.766-.308-1.663-.37A72 72 0 0 0 12 4c-1.827 0-3.547.091-4.81.171c-.902.069-1.347.103-1.661.377q-.062.054-.115.115zm13.264 7.986c-.068-.571-.097-.863-.365-1.068c-.263-.2-.572-.171-1.171-.109c-.275.029-.589.063-.954.114a6 6 0 0 0-.868.178c-.532.154-.8.228-1.2.748c-.406.52-.406.937-.406 1.77v4.542c0 .548 0 .828.183 1c.177.171.468.171 1.051.171h1.537c.96 0 1.434 0 1.788-.308c.354-.309.394-.737.474-1.589c.165-1.814.142-3.64-.069-5.449m-12.99-1.068c-.268.205-.296.491-.365 1.068a26.2 26.2 0 0 0-.069 5.45c.08.856.115 1.279.475 1.588c.354.308.828.308 1.788.308h1.536c.583 0 .874 0 1.051-.171c.183-.172.183-.452.183-1v-4.541c0-.84 0-1.257-.4-1.771c-.411-.526-.674-.6-1.205-.754a7 7 0 0 0-.868-.183l-.954-.103c-.606-.057-.909-.091-1.171.114z");
}

.ft5dv1b6b {
  fill: none;
}

.ol-o90bcc {
  fill: var(--svg-color--178dd0, #178dd0);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
