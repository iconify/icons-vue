<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/codksgb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="codksgb6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:square-alert-sharp" /></template>
