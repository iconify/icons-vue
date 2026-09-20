<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/keqzm32_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="keqzm32_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:share-circle" /></template>
