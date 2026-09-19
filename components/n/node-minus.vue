<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh0syhlhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uh0syhlhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:node-minus" /></template>
