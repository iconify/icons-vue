<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xzk6xmbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xzk6xmbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:number-small-1" /></template>
