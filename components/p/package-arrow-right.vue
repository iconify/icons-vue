<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e6tmqx8vt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6tmqx8vt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:package-arrow-right" /></template>
