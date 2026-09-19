<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_ijudcua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="d_ijudcua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:south-wind-mahjong" /></template>
