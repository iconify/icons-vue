<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd4o3lbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="rd4o3lbxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:outlook" /></template>
