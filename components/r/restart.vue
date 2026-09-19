<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2yhh17rp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u2yhh17rp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:restart" /></template>
