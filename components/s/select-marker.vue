<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuc0peqme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yuc0peqme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:select-marker" /></template>
