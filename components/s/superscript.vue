<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2fuo2bms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l2fuo2bms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:superscript" /></template>
