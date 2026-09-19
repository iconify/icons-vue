<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fju0pbb_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="fju0pbb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:polyline-pt" /></template>
