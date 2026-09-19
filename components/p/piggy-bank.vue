<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aobyfqzlx.css';
import '../../css/a/a78cr7b8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aobyfqzlx"/><path class="a78cr7b8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:piggy-bank" /></template>
