<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu8wy8bjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tu8wy8bjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rabbit-line" /></template>
