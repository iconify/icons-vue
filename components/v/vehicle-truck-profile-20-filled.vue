<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c4y3iobvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vehicle-truck-profile-20-filled" /></template>
<style>
.c4y3iobvd {
  fill: currentColor;
  d: path("M2.042 4.75c0-.966.784-1.75 1.75-1.75h8.459c.966 0 1.75.784 1.75 1.75V6h.881a1.5 1.5 0 0 1 1.342.83l1.618 3.235a1.5 1.5 0 0 1 .159.67V14.5a1.5 1.5 0 0 1-1.5 1.5h-1.55a2.5 2.5 0 0 1-4.9 0h-1.1a2.5 2.5 0 0 1-4.9 0h-.259a1.75 1.75 0 0 1-1.75-1.75zM14.001 7v3h2.69L15.33 7.276A.5.5 0 0 0 14.883 7zm-7.5 7a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3m4.5 1.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 0 0-3 0");
}

</style>
