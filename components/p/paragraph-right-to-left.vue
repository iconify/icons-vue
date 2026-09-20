<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwuzo1b4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwuzo1b4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:paragraph-right-to-left" /></template>
