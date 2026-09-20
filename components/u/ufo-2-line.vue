<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/soq9j-sgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="soq9j-sgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ufo-2-line" /></template>
