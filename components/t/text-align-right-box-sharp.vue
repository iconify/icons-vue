<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbnbkpb1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbnbkpb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:text-align-right-box-sharp" /></template>
