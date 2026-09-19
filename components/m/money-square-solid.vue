<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dswrzxb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dswrzxb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:money-square-solid" /></template>
