<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxq98cb3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxq98cb3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:music-play" /></template>
