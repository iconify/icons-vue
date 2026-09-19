<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cq2drpblx.css';
import '../../css/g/gi07l0tvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="cq2drpblx"/><path class="gi07l0tvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:triangle-map" /></template>
