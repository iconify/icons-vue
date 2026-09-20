<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpujj_1gl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpujj_1gl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:notebook-remove" /></template>
