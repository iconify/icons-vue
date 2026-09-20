<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0ogmnb8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0ogmnb8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:money-pound-circle-fill" /></template>
