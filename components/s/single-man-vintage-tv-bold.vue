<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw4x6rw-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dw4x6rw-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:single-man-vintage-tv-bold" /></template>
