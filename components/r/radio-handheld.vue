<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdiilpxab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdiilpxab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:radio-handheld" /></template>
