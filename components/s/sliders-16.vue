<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plrwr-bwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="plrwr-bwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:sliders-16" /></template>
