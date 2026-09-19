<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nr8m7obju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="nr8m7obju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:plan-view" /></template>
