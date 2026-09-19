<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k85w4fbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="k85w4fbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:map-search" /></template>
