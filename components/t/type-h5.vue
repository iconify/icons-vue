<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q37h1n4jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q37h1n4jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:type-h5" /></template>
