<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmt21rbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmt21rbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:map-line" /></template>
