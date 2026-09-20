<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0wbvz2iy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r0wbvz2iy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-arrow-top-right" /></template>
