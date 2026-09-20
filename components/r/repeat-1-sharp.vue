<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgrr9qb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgrr9qb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:repeat-1-sharp" /></template>
