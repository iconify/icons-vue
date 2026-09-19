<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwddebkal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwddebkal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:mouse-pointer" /></template>
