<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mun4s9bhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mun4s9bhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:writing-system-hangul" /></template>
