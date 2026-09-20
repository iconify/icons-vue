<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p735e-b_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p735e-b_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:text-flow-rows" /></template>
