<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdbl3bnfw.css';
import '../../css/e/e2li34b1z.css';
import '../../css/x/xh-rjd76x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":16};
const content = `<path class="zdbl3bnfw"/><path class="e2li34b1z"/><path class="xh-rjd76x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:textarea" /></template>
