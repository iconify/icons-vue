<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3yoq-5dj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z3yoq-5dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:zos-sysplex" /></template>
