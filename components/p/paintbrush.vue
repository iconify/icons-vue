<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oy8a-7mcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="oy8a-7mcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:paintbrush" /></template>
