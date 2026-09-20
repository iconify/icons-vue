<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="sint6bcin"/><path clip-rule="evenodd" class="emvobb0ss"/><path class="vf0-fbcfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:zero" /></template>
<style>
.emvobb0ss {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 20.01a8.01 8.01 0 1 0 0-16.022a8.01 8.01 0 0 0 0 16.021m0 .494a8.505 8.505 0 1 0 0-17.01a8.505 8.505 0 0 0 0 17.01");
}

.ft5dv1b6b {
  fill: none;
}

.sint6bcin {
  fill: var(--svg-color--fce058, #fce058);
  fill-rule: evenodd;
  d: path("M12 20.505a8.506 8.506 0 1 0 0-17.011a8.506 8.506 0 0 0 0 17.01M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

.vf0-fbcfm {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.375 8.063h-6.75V9.75h4.106l-4.106 4.894v1.293h6.75V14.25h-4.039l4.039-4.877z");
}

</style>
