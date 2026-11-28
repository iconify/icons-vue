<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etuz80cyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etuz80cyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:share" /></template>
