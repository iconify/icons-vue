<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="mejbn8bye"/><path class="mue8y31lb"/><path class="b-kovd7qe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:meteorite-sharp" /></template>
<style>
.b-kovd7qe {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 10.25h.01m.99 5h.01m8.49-1.75h.01");
}

.mejbn8bye {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.88 9.49l1.74-2.98L6.5 5l1.65-.58l1.7-.59l1.65-.58l1.64.6l2.22.8l1.64.6l.94 1.47l2.12 3.31l.94 1.47l-.44 1.69l-.87 3.37l-.44 1.69l-1.6.7l-3.05 1.35l-1.6.7l-1.7-.42l-3.6-.91l-1.7-.42l-.6-1.64l-1.8-4.97L3 11z");
}

.mue8y31lb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.75 4.5l2.75 7.25l-1.25 8.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
