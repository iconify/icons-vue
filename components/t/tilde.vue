<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvg9dfb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvg9dfb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tilde" /></template>
