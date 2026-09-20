<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1lm0bb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1lm0bb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:xing-circle" /></template>
