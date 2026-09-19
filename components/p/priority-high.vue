<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l13qo9bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l13qo9bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:priority-high" /></template>
