<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i43ht4usc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i43ht4usc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:plug-fill" /></template>
