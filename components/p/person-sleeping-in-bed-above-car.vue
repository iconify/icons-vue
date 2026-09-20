<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7mr94yrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="x7mr94yrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:person-sleeping-in-bed-above-car" /></template>
