<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td5vqccml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td5vqccml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:video-wireless-outline" /></template>
