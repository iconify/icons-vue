<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgb8vqb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wgb8vqb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:select-alt-filled" /></template>
