<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr9y_5b1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":69.5,"height":59};
const content = `<path class="nr9y_5b1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ramp" /></template>
