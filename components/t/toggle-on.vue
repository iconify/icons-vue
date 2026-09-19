<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqalj6buc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":1280};
const content = `<path class="qqalj6buc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:toggle-on" /></template>
