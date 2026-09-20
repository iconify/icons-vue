<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/towov9bvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="towov9bvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:typhoon-line" /></template>
