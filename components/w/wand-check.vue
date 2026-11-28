<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usnj5m19l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usnj5m19l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:wand-check" /></template>
