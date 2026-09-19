<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo9q2tsch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1664};
const content = `<path class="xo9q2tsch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:windows" /></template>
