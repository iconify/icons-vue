<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edyj6dbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="edyj6dbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:water-drop-solid" /></template>
