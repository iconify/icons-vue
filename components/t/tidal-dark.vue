<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co5zxf4is.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1001,"height":667};
const content = `<path class="co5zxf4is"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tidal-dark" /></template>
