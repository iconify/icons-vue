<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9u58f8ga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="i9u58f8ga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:suitcase" /></template>
