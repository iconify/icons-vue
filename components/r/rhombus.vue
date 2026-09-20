<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmaxe4qiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmaxe4qiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rhombus" /></template>
