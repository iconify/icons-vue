<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o60kez9_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o60kez9_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:warning-filled" /></template>
