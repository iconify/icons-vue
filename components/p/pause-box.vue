<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wod6j874l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wod6j874l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pause-box" /></template>
