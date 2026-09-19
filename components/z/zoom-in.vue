<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrt9p0ian.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrt9p0ian"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:zoom-in" /></template>
