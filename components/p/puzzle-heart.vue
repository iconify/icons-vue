<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm1y5sbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lm1y5sbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:puzzle-heart" /></template>
