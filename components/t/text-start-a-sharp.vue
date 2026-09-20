<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2jc44cxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2jc44cxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:text-start-a-sharp" /></template>
