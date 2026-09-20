<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu4q4-rfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu4q4-rfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:page-layout-header" /></template>
