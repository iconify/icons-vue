<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yixkk7odo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yixkk7odo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:smoothing-iron-outline" /></template>
