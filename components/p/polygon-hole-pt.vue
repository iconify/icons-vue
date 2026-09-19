<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yor3-q3xn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="yor3-q3xn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:polygon-hole-pt" /></template>
