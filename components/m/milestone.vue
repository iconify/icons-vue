<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u84h5fbwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u84h5fbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:milestone" /></template>
