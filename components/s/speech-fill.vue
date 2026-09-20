<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug1e5o2al.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug1e5o2al"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:speech-fill" /></template>
