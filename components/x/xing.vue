<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhyaxmbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1408,"height":1664};
const content = `<path class="rhyaxmbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:xing" /></template>
