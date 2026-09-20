<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy54agbxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iy54agbxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:sun-snow-solid" /></template>
