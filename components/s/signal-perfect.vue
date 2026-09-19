<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_lf_tb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="r_lf_tb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:signal-perfect" /></template>
