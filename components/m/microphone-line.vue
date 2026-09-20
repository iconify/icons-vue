<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/woqxoebsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="woqxoebsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:microphone-line" /></template>
