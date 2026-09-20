<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7b80xumb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7b80xumb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:train-car-caboose" /></template>
