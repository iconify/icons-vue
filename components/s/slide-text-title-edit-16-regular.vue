<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="texo4-n_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-text-title-edit-16-regular" /></template>
<style>
.texo4-n_t {
  fill: currentColor;
  d: path("M1 5a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v.134a2.9 2.9 0 0 0-1-.131V5a1 1 0 0 0-1-1H3a1 1 0 0 0-1 1v6a1 1 0 0 0 1 1h3.476a3 3 0 0 0-.043.155L6.22 13H3a2 2 0 0 1-2-2zm10.678 1.265L9.944 8H5a1 1 0 0 1 0-2h6c.262 0 .5.1.678.265M7.98 11.377l4.83-4.83a1.87 1.87 0 1 1 2.644 2.646l-4.83 4.829a2.2 2.2 0 0 1-1.02.578l-1.498.374a.89.89 0 0 1-1.079-1.078l.375-1.498a2.2 2.2 0 0 1 .578-1.02");
}

</style>
