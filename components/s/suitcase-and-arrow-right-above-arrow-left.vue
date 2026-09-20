<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew69n7dgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ew69n7dgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:suitcase-and-arrow-right-above-arrow-left" /></template>
