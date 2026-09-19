<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bc9ngvbus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bc9ngvbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:patch-question-fill" /></template>
