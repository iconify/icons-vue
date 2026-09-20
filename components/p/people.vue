<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifbbgy5pl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ifbbgy5pl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:people" /></template>
