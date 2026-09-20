<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhb07vwbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dhb07vwbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:v-kontakte-logo-block" /></template>
