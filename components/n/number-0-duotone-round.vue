<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ccijvbbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccijvbbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:number-0-duotone-round" /></template>
