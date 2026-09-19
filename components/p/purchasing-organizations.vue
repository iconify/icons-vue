<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6fj7fx9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z6fj7fx9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:purchasing-organizations" /></template>
