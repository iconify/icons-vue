<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa-uioj6p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fa-uioj6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:parking-line" /></template>
