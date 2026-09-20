<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nczsefc6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nczsefc6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:receipt-text-plus-outline" /></template>
