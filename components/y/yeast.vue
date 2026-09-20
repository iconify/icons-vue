<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxr1tjb9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxr1tjb9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:yeast" /></template>
