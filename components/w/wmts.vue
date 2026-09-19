<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4tjj46yl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="s4tjj46yl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:wmts" /></template>
