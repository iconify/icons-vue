<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xoksj6-5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="xoksj6-5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:rectangle-outline" /></template>
