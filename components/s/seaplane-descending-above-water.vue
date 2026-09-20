<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3793b6te.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p3793b6te"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:seaplane-descending-above-water" /></template>
