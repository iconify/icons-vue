<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkv-isb8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zkv-isb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:stand-by" /></template>
