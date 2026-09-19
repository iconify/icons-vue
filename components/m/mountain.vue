<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4f2fpnrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l4f2fpnrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:mountain" /></template>
