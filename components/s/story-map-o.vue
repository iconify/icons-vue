<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw99l1bzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="cw99l1bzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:story-map-o" /></template>
