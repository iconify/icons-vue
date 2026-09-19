<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv9w3mbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":271,"height":512};
const content = `<path class="zv9w3mbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:scratch" /></template>
