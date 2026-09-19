<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-r11kbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u-r11kbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:nav-arrow-left-solid" /></template>
