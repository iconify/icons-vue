<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rs1y6trep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rs1y6trep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:worm" /></template>
