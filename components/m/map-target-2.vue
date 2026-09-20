<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ygo8ey9ii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygo8ey9ii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:map-target-2" /></template>
