<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1zepsbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j1zepsbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:minus" /></template>
