<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz4wp-bec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lz4wp-bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:punctuation-check" /></template>
