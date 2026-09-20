<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujo66obxz.css';
import '../../css/q/q4yf1rbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ujo66obxz"/><path class="q4yf1rbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:tab-external-16" /></template>
