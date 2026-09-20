<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvy6d57rr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xvy6d57rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:marketing-outline" /></template>
