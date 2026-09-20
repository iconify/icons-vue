<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-vb4pags.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-vb4pags"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:vectorworks" /></template>
