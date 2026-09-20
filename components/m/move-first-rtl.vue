<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_ckmcczc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r_ckmcczc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:move-first-rtl" /></template>
