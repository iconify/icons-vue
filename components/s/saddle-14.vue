<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpmhpbb4z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="xpmhpbb4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:saddle-14" /></template>
