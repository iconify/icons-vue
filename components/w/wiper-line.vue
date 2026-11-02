<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyh-adcgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyh-adcgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wiper-line" /></template>
