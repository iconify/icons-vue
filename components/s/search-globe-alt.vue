<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yss197btb.css';
import '../../css/i/iabrmvfcy.css';
import '../../css/c/c5gmrlmbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="yss197btb"/><path class="iabrmvfcy"/><path class="c5gmrlmbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:search-globe-alt" /></template>
