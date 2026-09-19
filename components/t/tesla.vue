<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj2x4e0dv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="pj2x4e0dv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:tesla" /></template>
