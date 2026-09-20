<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e1z08kbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1z08kbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:star-box" /></template>
