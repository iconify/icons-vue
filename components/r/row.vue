<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl9xnabwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pl9xnabwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:row" /></template>
