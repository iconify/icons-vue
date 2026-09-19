<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbpijbb8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lbpijbb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:production-service" /></template>
