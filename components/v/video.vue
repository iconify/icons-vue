<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anvo63bjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="anvo63bjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:video" /></template>
