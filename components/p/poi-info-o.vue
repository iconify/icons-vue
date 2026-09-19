<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/je4z95b1p.css';
import '../../css/d/dxj4yybcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="je4z95b1p"/><path class="dxj4yybcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:poi-info-o" /></template>
