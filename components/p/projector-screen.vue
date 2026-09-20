<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d35yl_bae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d35yl_bae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:projector-screen" /></template>
