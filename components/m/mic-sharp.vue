<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs21tvndn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs21tvndn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:mic-sharp" /></template>
