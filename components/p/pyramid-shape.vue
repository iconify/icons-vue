<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbj-b-sfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="zbj-b-sfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pyramid-shape" /></template>
