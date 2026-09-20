<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf49yac9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf49yac9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:train-line" /></template>
