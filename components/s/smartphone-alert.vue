<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f78g2-ujg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f78g2-ujg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:smartphone-alert" /></template>
