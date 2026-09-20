<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f215n60kr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f215n60kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:math-compass-variant" /></template>
