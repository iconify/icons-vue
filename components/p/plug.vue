<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/toh88ac3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="toh88ac3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:plug" /></template>
