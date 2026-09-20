<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aeonlwh5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aeonlwh5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:user-x-sharp" /></template>
