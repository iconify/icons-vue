<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ol8x4ezvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ol8x4ezvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:music-2-solid" /></template>
