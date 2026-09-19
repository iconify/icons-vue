<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6nmzbcnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t6nmzbcnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:portfolio" /></template>
