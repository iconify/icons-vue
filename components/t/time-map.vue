<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5hzx-o4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="a5hzx-o4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:time-map" /></template>
