<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag3297hsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ag3297hsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:vertical-slider-square-remix" /></template>
