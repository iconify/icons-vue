<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me2jhw4ij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="me2jhw4ij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:office-building-minus-outline" /></template>
