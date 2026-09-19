<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drgua2bcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="drgua2bcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:swipe-map-h" /></template>
