<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zam1hz-xe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="zam1hz-xe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:merge-vertical" /></template>
