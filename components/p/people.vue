<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-3-5ybig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="a-3-5ybig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:people" /></template>
