<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcstz7b8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcstz7b8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:shape-circle" /></template>
