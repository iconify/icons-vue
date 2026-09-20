<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhaaw35sz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nhaaw35sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:wifi-disabled-remix" /></template>
