<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nky2nab7l.css';
import '../../css/t/t0669_bln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nky2nab7l"/><path class="t0669_bln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:wrench-screwdriver-16-solid" /></template>
