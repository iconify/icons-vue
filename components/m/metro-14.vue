<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hex2xscoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="hex2xscoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:metro-14" /></template>
