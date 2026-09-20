<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuf1hebgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="yuf1hebgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:steps-14" /></template>
