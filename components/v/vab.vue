<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy1d94bxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fy1d94bxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:vab" /></template>
