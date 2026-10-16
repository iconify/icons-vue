<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2gs_oovh.css';
import '../../css/r/rme-dq93w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z2gs_oovh"/><path class="rme-dq93w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scroll-20-bold" /></template>
