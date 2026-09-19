<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx0z7v04o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xx0z7v04o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ruler" /></template>
