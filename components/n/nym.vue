<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pde511gmx"><path clip-rule="evenodd" class="zlu6ccbna"/><path class="s-4sseo7q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nym" /></template>
<style>
.pde511gmx {
  fill: var(--svg-color--181b1e, #181b1e);
}

.s-4sseo7q {
  d: path("M7.235 17.289V6.722a7.2 7.2 0 0 1 1.589-1.075l6.353 9.9v-9.9a7.3 7.3 0 0 1 1.588 1.117v10.53a7.4 7.4 0 0 1-1.588 1.059L8.824 8.42v9.932a8.5 8.5 0 0 1-1.589-1.064");
}

.zlu6ccbna {
  fill-rule: evenodd;
  d: path("M21 12a9 9 0 1 0-18 0a9 9 0 0 0 18 0m-1.059 0a7.941 7.941 0 1 0-15.883 0a7.941 7.941 0 0 0 15.883 0");
}

</style>
