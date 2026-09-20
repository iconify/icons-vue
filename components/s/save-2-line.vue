<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn3ahzsej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vn3ahzsej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:save-2-line" /></template>
