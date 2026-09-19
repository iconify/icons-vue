<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti7oxnffl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ti7oxnffl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:whatsapp" /></template>
