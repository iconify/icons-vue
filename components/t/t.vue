<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsprk2c2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bsprk2c2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:t" /></template>
