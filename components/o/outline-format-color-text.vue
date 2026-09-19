<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bc7fd2b-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-format-color-text" /></template>
<style>
.bc7fd2b-f {
  fill: currentColor;
  d: path("M2 20h20v4H2zm3.49-3h2.42l1.27-3.58h5.65L16.09 17h2.42L13.25 3h-2.5zm4.42-5.61l2.03-5.79h.12l2.03 5.79z");
}

</style>
