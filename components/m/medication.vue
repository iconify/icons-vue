<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5kn33byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u5kn33byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:medication" /></template>
