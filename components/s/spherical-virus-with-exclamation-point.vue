<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yavt7lb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yavt7lb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:spherical-virus-with-exclamation-point" /></template>
