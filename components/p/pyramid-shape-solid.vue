<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-mrup4sw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m-mrup4sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:pyramid-shape-solid" /></template>
