<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h87yt6bpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:splitscreen-landscape-add" /></template>
<style>
.h87yt6bpz {
  fill: currentColor;
  d: path("M19.77 8V6h-2V5h2V3h1v2h2v1h-2v2zM6.384 15.616h4.423V8.385H6.385zM21 10.286v7.099q0 .666-.475 1.14t-1.14.475H4.615q-.666 0-1.14-.475T3 17.386V6.615q0-.666.475-1.14T4.615 5h10.793q-.012.125-.017.25q-.007.125-.007.25q0 .816.253 1.547q.253.732.69 1.338h-3.135v7.23h4.424v-6.04q.507.354 1.116.563t1.268.247q.256.019.506-.007t.494-.092");
}

</style>
