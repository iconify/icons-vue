<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye5x6bbrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ye5x6bbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:receipt-add-remix" /></template>
