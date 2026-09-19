<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxc0abc3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uxc0abc3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:number-small-8" /></template>
