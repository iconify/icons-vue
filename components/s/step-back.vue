<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d11_ivbta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d11_ivbta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:step-back" /></template>
