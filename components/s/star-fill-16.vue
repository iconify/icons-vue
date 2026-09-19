<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4a9e_bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t4a9e_bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:star-fill-16" /></template>
