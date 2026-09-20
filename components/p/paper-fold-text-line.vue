<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5s7h4b-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5s7h4b-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:paper-fold-text-line" /></template>
