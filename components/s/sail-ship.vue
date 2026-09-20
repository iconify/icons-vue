<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wmynibc-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="wmynibc-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:sail-ship" /></template>
