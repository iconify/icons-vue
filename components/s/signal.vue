<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7wxdacdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1536};
const content = `<path class="t7wxdacdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:signal" /></template>
