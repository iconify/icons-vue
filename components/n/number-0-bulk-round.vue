<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dai24z1ii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dai24z1ii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:number-0-bulk-round" /></template>
