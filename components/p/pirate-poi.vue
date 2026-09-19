<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va0q3tbnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="va0q3tbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:pirate-poi" /></template>
