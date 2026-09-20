<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l45ra6buz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l45ra6buz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:turn-left" /></template>
