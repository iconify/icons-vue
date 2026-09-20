<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy9v6jbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fy9v6jbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:smiley-mask-solid" /></template>
