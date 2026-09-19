<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujmtbcmfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ujmtbcmfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:source-control" /></template>
