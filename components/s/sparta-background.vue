<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="o1vqthzdy"/><path class="dbm1fy1wv"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sparta-background" /></template>
<style>
.dbm1fy1wv {
  fill: var(--svg-color--fff, #fff);
  d: path("m10.547 19.999l.154-.031c-.07-2.782-.342-5.573.405-8.284c-.13-.107-.189-.182-.267-.217c-.406-.178-.811-.359-1.228-.513c-.732-.27-1.015-.737-.883-1.572c.16.075.305.147.456.209c.493.203.98.433 1.487.597c.674.217.805.383.7 1.066c-.07.466-.162.93-.199 1.398c-.034.427.391 1.012.733 1.081c.297.061.755-.303.9-.768c.058-.186.031-.404.01-.605c-.048-.468-.126-.931-.174-1.399c-.041-.4.18-.61.57-.74c.55-.185 1.083-.418 1.623-.631c.147-.058.293-.124.458-.194c.076.942-.176 1.298-1.018 1.594c-.455.16-.889.375-1.391.591c.75 2.818.466 5.616.509 8.419a3.3 3.3 0 0 0 .504-.74c.117-.222.21-.456.319-.684c.515-1.082 1.052-2.157 1.535-3.252c.15-.34.231-.739.236-1.112c.021-1.836.015-3.673 0-5.51c-.004-.438-.027-.899-.167-1.308c-.25-.732-.475-1.52-.937-2.127c-.832-1.094-2.104-1.393-3.474-1.222c-1.095.136-2.063.607-2.559 1.553c-.522.994-.852 2.077-.844 3.222c.013 1.809-.014 3.616 0 5.423c.001.29.046.6.165.86c.687 1.506 1.4 3.002 2.111 4.5c.067.14.176.265.266.396");
}

.ft5dv1b6b {
  fill: none;
}

.o1vqthzdy {
  fill: var(--svg-color--fa2714, #fa2714);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
