<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlk0x0bsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlk0x0bsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:map-pin-x-inside-fill" /></template>
