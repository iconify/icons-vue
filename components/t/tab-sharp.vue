<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttj_bebjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttj_bebjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:tab-sharp" /></template>
