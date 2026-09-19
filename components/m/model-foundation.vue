<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq8qz_u7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zq8qz_u7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:model-foundation" /></template>
