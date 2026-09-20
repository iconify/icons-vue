<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9qzhvb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="u9qzhvb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:wheelbarrow" /></template>
