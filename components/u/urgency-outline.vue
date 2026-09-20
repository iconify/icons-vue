<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_eyktb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u_eyktb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:urgency-outline" /></template>
