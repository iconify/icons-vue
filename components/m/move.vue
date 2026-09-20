<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve2a2gbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ve2a2gbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:move" /></template>
