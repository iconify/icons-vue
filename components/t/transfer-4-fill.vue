<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcr1ef8xs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcr1ef8xs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:transfer-4-fill" /></template>
