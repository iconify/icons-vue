<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k42_wfgps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k42_wfgps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:queue" /></template>
