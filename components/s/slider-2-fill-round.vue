<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r093a8ojm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r093a8ojm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:slider-2-fill-round" /></template>
