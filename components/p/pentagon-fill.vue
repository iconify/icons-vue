<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yef25-vzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yef25-vzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:pentagon-fill" /></template>
