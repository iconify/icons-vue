<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu-l12apa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cu-l12apa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:news-paper-remix" /></template>
