<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf68k4yfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mf68k4yfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:yadnsb" /></template>
