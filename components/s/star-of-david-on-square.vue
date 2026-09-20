<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jv2clib9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jv2clib9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:star-of-david-on-square" /></template>
