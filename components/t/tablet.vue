<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqc9t5egf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="zqc9t5egf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:tablet" /></template>
