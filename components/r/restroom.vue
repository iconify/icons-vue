<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnyx5vbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="rnyx5vbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:restroom" /></template>
