<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9gpmfb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="r9gpmfb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pound" /></template>
