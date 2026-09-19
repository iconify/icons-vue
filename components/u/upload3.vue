<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1_ve62yi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m1_ve62yi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:upload3" /></template>
