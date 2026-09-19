<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/saivc4b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="saivc4b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:top-programs" /></template>
