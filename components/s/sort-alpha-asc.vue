<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_840f2vp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="x_840f2vp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:sort-alpha-asc" /></template>
