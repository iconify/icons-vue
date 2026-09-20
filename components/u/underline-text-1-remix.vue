<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkvkrobrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qkvkrobrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:underline-text-1-remix" /></template>
