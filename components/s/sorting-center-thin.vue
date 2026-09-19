<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/funbpuq8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="funbpuq8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:sorting-center-thin" /></template>
