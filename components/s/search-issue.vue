<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw1el3vtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="kw1el3vtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:search-issue" /></template>
