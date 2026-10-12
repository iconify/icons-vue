<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lf3sb2bws"/><path class="ntazt1bsz"/><path class="spx3zkb6w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wax-seal" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lf3sb2bws {
  d: path("M11.25 2.95c1.22.2 1.91.84 3.21 1.41s2.46.45 3.3 1.43c.85.98.58 2.08.93 3.47c.35 1.38.93 2.25.83 3.45s-1.07 1.5-1.34 2.54c-.28 1.04.06 1.8-.02 2.67s.04 1.35-.38 1.68c-.43.33-.76.07-1.73-.04c-.97-.1-1.88-.5-3.14-.48c-1.25.01-1.93.86-3.14.54c-1.2-.32-1.7-1.32-2.88-2.14c-1.18-.83-2.34-.87-3-1.98s-.2-2.15-.31-3.58c-.11-1.42-.68-2.33-.22-3.54s1.51-1.5 2.52-2.5c1-1.01 1.42-1.94 2.5-2.52c1.07-.59 1.65-.61 2.87-.41");
}

.ntazt1bsz {
  d: path("M16 11.25a4.75 4.75 0 1 1-9.5 0a4.75 4.75 0 0 1 9.5 0");
}

.spx3zkb6w {
  d: path("M12.6 9.5c-.3-.4-.8-.6-1.35-.6c-.75 0-1.4.45-1.4 1.05c0 1.5 2.8.9 2.8 2.45c0 .65-.65 1.1-1.4 1.1c-.6 0-1.1-.2-1.4-.6");
}

</style>
