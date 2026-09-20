<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khsclibwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="khsclibwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:star-plus-empty" /></template>
