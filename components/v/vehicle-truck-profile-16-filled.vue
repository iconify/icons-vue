<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="orwcilwco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vehicle-truck-profile-16-filled" /></template>
<style>
.orwcilwco {
  fill: currentColor;
  d: path("M2 3.75C2 2.784 2.784 2 3.75 2h5.5c.967 0 1.75.784 1.75 1.75V4h.382a1.5 1.5 0 0 1 1.342.83l1.118 2.235a1.5 1.5 0 0 1 .158.671V11a1.5 1.5 0 0 1-1.5 1.5h-.563a2 2 0 0 1-3.874 0H6.937a2 2 0 0 1-3.907-.155A1.75 1.75 0 0 1 2 10.75zM11 5v2h1.691l-.862-1.724A.5.5 0 0 0 11.382 5zm-6 6a1 1 0 1 0 0 2a1 1 0 0 0 0-2m4 1a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
