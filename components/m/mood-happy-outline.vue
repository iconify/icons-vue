<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjugbmb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qjugbmb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:mood-happy-outline" /></template>
