<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4oy1rbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="p4oy1rbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:xmark-shield-fill" /></template>
