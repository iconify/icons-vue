<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uiw4tobef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1344,"height":1664};
const content = `<path class="uiw4tobef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:yahoo" /></template>
