<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztylrtbjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztylrtbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:wand-filled" /></template>
