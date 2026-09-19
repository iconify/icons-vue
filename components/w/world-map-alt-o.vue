<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld3-dq87l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ld3-dq87l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:world-map-alt-o" /></template>
