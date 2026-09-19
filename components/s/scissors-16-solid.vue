<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d28tlbcov.css';
import '../../css/r/r173rlbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d28tlbcov"/><path class="r173rlbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:scissors-16-solid" /></template>
