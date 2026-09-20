<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c84me5bzl.css';
import '../../css/d/dty59pw6a.css';
import '../../css/i/i0aiaupcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c84me5bzl"/><path class="dty59pw6a"/><path class="i0aiaupcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:rss" /></template>
