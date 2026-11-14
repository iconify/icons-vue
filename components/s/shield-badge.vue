<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hnvnn0bgl"/><path class="zc3atnb2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shield-badge" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hnvnn0bgl {
  d: path("m12 2.75l7.5 2.75v6c0 4.7-3.1 8-7.5 9.75c-4.4-1.75-7.5-5.05-7.5-9.75v-6Z");
}

.zc3atnb2h {
  d: path("m12.75 7.625l.379.821a1.5 1.5 0 0 0 1.255.867l.866.062a.801.801 0 0 1 .509 1.366l-.682.682a1.5 1.5 0 0 0-.406 1.375l.204.952a.827.827 0 0 1-1.201.901l-.963-.518a1.5 1.5 0 0 0-1.422 0l-.963.518a.827.827 0 0 1-1.201-.901l.204-.952a1.5 1.5 0 0 0-.406-1.375l-.682-.682a.801.801 0 0 1 .509-1.366l.866-.062a1.5 1.5 0 0 0 1.255-.867l.379-.821a.826.826 0 0 1 1.5 0");
}

</style>
