<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh0lcaceg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="qh0lcaceg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:paintbrush-fill" /></template>
