<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu3_yhbce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xu3_yhbce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:user" /></template>
