<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzszqsj-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="wzszqsj-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:satellite-earth" /></template>
