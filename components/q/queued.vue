<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1nqv73bw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y1nqv73bw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:queued" /></template>
