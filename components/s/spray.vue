<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5eoflcbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="d5eoflcbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:spray" /></template>
