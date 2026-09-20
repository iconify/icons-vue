<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="uc5ii03tg"/><path clip-rule="evenodd" class="umexo8xcx"/><path clip-rule="evenodd" class="rrcwzdbfa"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:megaphone-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rrcwzdbfa {
  fill-rule: evenodd;
  d: path("M6.424 12H5.84l-.766 3h.583zm-.584-2a2 2 0 0 0-1.938 1.506l-1.084 4.247A1 1 0 0 0 3.788 17h1.87a2 2 0 0 0 1.937-1.505l.767-3A2 2 0 0 0 6.424 10zm13.192-5.555a1 1 0 0 1-.277 1.387l-1.5 1a1 1 0 0 1-1.11-1.664l1.5-1a1 1 0 0 1 1.387.277M15.7 8.6a1 1 0 0 1 1-1h1.5a1 1 0 0 1 0 2h-1.5a1 1 0 0 1-1-1m.234 1.909a1 1 0 0 1 1.409-.123l1.38 1.16a1 1 0 0 1-1.286 1.531l-1.38-1.16a1 1 0 0 1-.123-1.408");
}

.uc5ii03tg {
  fill-rule: evenodd;
  d: path("m7.4 10.054l5.6 1.527V5.62L7.4 7.146zm-2 .764a1 1 0 0 0 .737.965l7.6 2.073A1 1 0 0 0 15 12.89V4.309a1 1 0 0 0-1.263-.965l-7.6 2.073a1 1 0 0 0-.737.965z");
}

.umexo8xcx {
  fill-rule: evenodd;
  d: path("M5.016 9.8V7.4H3.969a2.43 2.43 0 0 0 .004 2.4zm1 2a1 1 0 0 0 1-1V6.4a1 1 0 0 0-1-1H3.253a.55.55 0 0 0-.4.172c-1.602 1.691-1.595 4.353-.002 6.052a.56.56 0 0 0 .405.176z");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
