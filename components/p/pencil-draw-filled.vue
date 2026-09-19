<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mip59zb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mip59zb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:pencil-draw-filled" /></template>
