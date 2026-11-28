<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqa84pstj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqa84pstj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:water-glass" /></template>
