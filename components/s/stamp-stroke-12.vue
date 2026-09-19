<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khql2o0xz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="khql2o0xz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:stamp-stroke-12" /></template>
