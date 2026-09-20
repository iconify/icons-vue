<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_60rg5hw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_60rg5hw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:pencil-1" /></template>
