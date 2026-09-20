<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkqkbp-3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="rkqkbp-3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:travel-map-navigation-arrow-off-compass-arrow-map-bearing-navigation-maps-heading-gps-off-disable" /></template>
