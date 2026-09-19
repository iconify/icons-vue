<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ow1wj2bms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ow1wj2bms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:upload" /></template>
