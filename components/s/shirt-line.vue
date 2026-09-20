<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqizjvl4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqizjvl4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shirt-line" /></template>
