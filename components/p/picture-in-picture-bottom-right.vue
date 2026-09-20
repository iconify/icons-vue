<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxg4ymi-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxg4ymi-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:picture-in-picture-bottom-right" /></template>
