<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf1ev1bin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hf1ev1bin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:shield-16" /></template>
