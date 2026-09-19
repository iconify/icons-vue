<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apon61bjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1728,"height":1664};
const content = `<path class="apon61bjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:pie-chart" /></template>
