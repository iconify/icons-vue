<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlmv-7cof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xlmv-7cof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:volume-muted-stroke-12" /></template>
