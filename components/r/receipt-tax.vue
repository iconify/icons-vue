<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7hdcac9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7hdcac9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:receipt-tax" /></template>
