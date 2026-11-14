<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddvgu8bvv.css';
import '../../css/v/vyzc02u8i.css';
import '../../css/c/ckyxfmymk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ddvgu8bvv"><path class="vyzc02u8i"/><path class="ckyxfmymk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:star-circle" /></template>
