<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3q760j9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d3q760j9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:sun-solid" /></template>
