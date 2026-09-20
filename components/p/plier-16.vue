<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru9u8d0sx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ru9u8d0sx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:plier-16" /></template>
