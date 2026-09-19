<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs4k7ccaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="fs4k7ccaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:strikethrough" /></template>
