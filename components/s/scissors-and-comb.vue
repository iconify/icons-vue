<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o63smnbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o63smnbgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:scissors-and-comb" /></template>
