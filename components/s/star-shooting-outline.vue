<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5cnq49py.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5cnq49py"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:star-shooting-outline" /></template>
