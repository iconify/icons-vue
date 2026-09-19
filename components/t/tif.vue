<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z02o_h7tc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z02o_h7tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:tif" /></template>
