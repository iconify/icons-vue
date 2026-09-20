<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c08ya8vwu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c08ya8vwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wardrobe" /></template>
