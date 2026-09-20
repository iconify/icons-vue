<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzjmspaxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzjmspaxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rotate-counter-clockwise" /></template>
