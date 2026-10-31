<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eaoiwm7ah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eaoiwm7ah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wavy-minus-fill-round" /></template>
