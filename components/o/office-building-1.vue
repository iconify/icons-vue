<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqubr3bsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="xqubr3bsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:office-building-1" /></template>
