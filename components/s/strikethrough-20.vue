<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctlj9gncl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ctlj9gncl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:strikethrough-20" /></template>
