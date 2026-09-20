<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dj9_3lb1x"/><path class="l3gjt368z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nmx" /></template>
<style>
.dj9_3lb1x {
  fill: var(--svg-color--00a0ff, #00a0ff);
  d: path("M3.071 13.119a9.007 9.007 0 0 1 17.282-4.504h-.99a2.98 2.98 0 0 0-2.095.845l-4.137 4.222V9.066c0-.901-.732-1.565-1.503-1.576c-.366 0-.743.123-1.053.416l-5.612 4.982a.83.83 0 0 1-.574.23z");
}

.ft5dv1b6b {
  fill: none;
}

.l3gjt368z {
  fill: var(--svg-color--80cfff, #80cfff);
  d: path("M12.005 21a9.006 9.006 0 0 0 8.922-10.132h-1.565a.82.82 0 0 0-.585.242l-5.348 4.953a1.498 1.498 0 0 1-2.55-1.086V10.54l-4.442 4.177c-.557.523-1.294.647-2.054.647H3.65C4.99 18.675 8.289 21 12.005 21");
}

</style>
