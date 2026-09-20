<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dze2-e2jz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dze2-e2jz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:ticket-text-line" /></template>
