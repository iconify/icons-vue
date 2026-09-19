<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0c0s1bpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d0c0s1bpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:word" /></template>
