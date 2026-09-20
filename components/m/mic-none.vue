<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx0dswoqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hx0dswoqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:mic-none" /></template>
