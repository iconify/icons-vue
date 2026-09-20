<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hq8y7_swj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hq8y7_swj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:percent-outline" /></template>
