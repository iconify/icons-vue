<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cporbno1m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cporbno1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:z" /></template>
