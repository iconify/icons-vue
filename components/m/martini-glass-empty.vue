<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4md5kkgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t4md5kkgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:martini-glass-empty" /></template>
