<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6ffppbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6ffppbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:neural-network-round" /></template>
