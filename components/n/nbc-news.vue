<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="robuzeb4y"/><path class="t3u8iewpj"/><path class="b8aukjowi"/><path class="puh9wzbcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nbc-news" /></template>
<style>
.b8aukjowi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.261 20.335c-1.625-2.624-5.5-2.444-6.875.32l-6.168 12.392l11.769-7.288a3.94 3.94 0 0 0 1.274-5.424");
}

.puh9wzbcq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.274 22.956l.946 10.084l6.172-12.382a3.95 3.95 0 0 0-1.78-5.283c-2.761-1.372-5.968.816-5.671 3.892l.037.316c2.057-.316 3.225.24 3.225.24c-1.205.927-2.133 1.825-2.929 3.133v.019z");
}

.robuzeb4y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4 29.108c0-3.087 3.39-4.975 6.014-3.35l11.768 7.289H7.939A3.94 3.94 0 0 1 4 29.107");
}

.t3u8iewpj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.739 20.335c1.625-2.624 5.5-2.444 6.875.32l6.168 12.392l-11.768-7.288a3.94 3.94 0 0 1-1.275-5.424m8.647-4.963c2.763-1.375 5.963.818 5.678 3.892l-1.282 13.783l-6.168-12.393a3.94 3.94 0 0 1 1.772-5.282M44 29.108c0-3.087-3.39-4.975-6.013-3.35l-11.769 7.289h13.843A3.94 3.94 0 0 0 44 29.107");
}

</style>
