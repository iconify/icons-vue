<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifbcj67mj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ifbcj67mj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:police-14" /></template>
