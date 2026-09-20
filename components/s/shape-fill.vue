<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvgb31bue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvgb31bue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shape-fill" /></template>
