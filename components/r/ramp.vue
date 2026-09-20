<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rdx-0ob6a"/><path class="tx1r43n9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ramp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.rdx-0ob6a {
  fill: var(--svg-color--00b5d1, #00b5d1);
  d: path("M14.368 13.455L12 14.905l-2.369-1.45v-2.906L12 9.092l2.368 1.457z");
}

.tx1r43n9v {
  fill: var(--svg-color--0d285a, #0d285a);
  d: path("M12 3L4.42 7.503v8.994L12 21l7.579-4.503V7.503zM8.21 14.18V9.797L12 7.641l3.79 2.156v4.384l-3.818 2.186zm0 2.527v-1.522l5.056 2.964l-1.266.756zm9.474-1.255L14.11 17.65l-1.31-.784l3.937-2.197v-5.36L12 6.672L7.263 9.309v6.77l-.947-.688V8.608L12 5.218l5.684 3.33z");
}

</style>
