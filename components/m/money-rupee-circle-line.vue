<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufsfxe4uy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufsfxe4uy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:money-rupee-circle-line" /></template>
