<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gqgdfndmd"/><path class="j0597jz_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pdex" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gqgdfndmd {
  fill: var(--svg-color--fff, #fff);
  d: path("M21 18.755v-2.54l-4.219-4.212H14.25zM3 5.64v2.47l4.291 4.537H9.75zM5.25 3h2.46l4.254 4.203L16.18 3h2.57L12 9.776zm0 18h2.46l4.253-4.202L16.18 21h2.571L12 14.266z");
}

.j0597jz_a {
  fill: var(--svg-color--e6007a, #e6007a);
  d: path("M12 13.29a1.286 1.286 0 1 0 0-2.573a1.286 1.286 0 0 0 0 2.573");
}

</style>
