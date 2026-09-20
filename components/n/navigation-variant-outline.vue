<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5rh0obzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5rh0obzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:navigation-variant-outline" /></template>
