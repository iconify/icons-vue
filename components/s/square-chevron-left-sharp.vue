<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjs7sj05i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjs7sj05i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:square-chevron-left-sharp" /></template>
