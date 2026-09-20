<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll5m0r9ek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ll5m0r9ek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pause" /></template>
