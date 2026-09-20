<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ga-o0vbwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ga-o0vbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:recycle-1-flat" /></template>
