<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5y0zvbxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5y0zvbxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ring" /></template>
