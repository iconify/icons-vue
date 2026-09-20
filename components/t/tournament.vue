<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmib2_bat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmib2_bat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tournament" /></template>
