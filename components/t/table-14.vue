<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpi5iabqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="fpi5iabqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:table-14" /></template>
