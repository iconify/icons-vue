<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx8f4jktk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zx8f4jktk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-color-filter" /></template>
