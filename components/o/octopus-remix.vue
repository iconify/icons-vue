<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypbr28bfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ypbr28bfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:octopus-remix" /></template>
