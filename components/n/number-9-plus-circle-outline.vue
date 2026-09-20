<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfoqfbcpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfoqfbcpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:number-9-plus-circle-outline" /></template>
