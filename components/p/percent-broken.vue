<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r94g1nb8h"/><path class="a_uu7kb6r"/><path class="ecdombc4d"/><path class="fiiydj38s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:percent-broken" /></template>
<style>
.a_uu7kb6r {
  d: path("M12 12L5 19");
}

.ecdombc4d {
  d: path("M9 6.5C9 7.8807 7.8807 9 6.5 9C5.1193 9 4 7.8807 4 6.5C4 5.1193 5.1193 4 6.5 4C7.8807 4 9 5.1193 9 6.5Z");
}

.fiiydj38s {
  d: path("M20 17.5C20 18.8807 18.8807 20 17.5 20C16.1193 20 15 18.8807 15 17.5C15 16.1193 16.1193 15 17.5 15C18.8807 15 20 16.1193 20 17.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r94g1nb8h {
  d: path("M19 5L15.5 8.5");
}

</style>
