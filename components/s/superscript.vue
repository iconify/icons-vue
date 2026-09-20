<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5l55k5vn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="q5l55k5vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:superscript" /></template>
