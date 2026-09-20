<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jux0sgb4d.css';
import '../../css/i/i3h_fy-ls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jux0sgb4d"/><path class="i3h_fy-ls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:power-button" /></template>
