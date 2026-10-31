<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/koc7tsbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="koc7tsbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:number-3-duotone-round" /></template>
