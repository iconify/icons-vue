<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eie2zmxnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="eie2zmxnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:money-check" /></template>
