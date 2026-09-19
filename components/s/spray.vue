<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjc-dy89z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tjc-dy89z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:spray" /></template>
