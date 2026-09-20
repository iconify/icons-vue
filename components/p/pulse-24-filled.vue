<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ua_u9xbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pulse-24-filled" /></template>
<style>
.ua_u9xbhr {
  fill: currentColor;
  d: path("m8.471 7.237l3.056 12.992c.233.993 1.63 1.04 1.929.065l2.945-9.58l.384 1.527a1 1 0 0 0 .97.756H21a1 1 0 1 0 0-2h-2.466l-1.069-4.241c-.247-.981-1.628-1.017-1.925-.05l-2.912 9.472L9.475 2.771c-.24-1.02-1.688-1.03-1.943-.014l-2.065 8.24H3a1 1 0 0 0 0 2h3.247a1 1 0 0 0 .97-.757z");
}

</style>
