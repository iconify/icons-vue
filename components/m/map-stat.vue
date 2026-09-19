<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n502x1bvx.css';
import '../../css/q/qcwre9owc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="n502x1bvx"/><path class="qcwre9owc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:map-stat" /></template>
