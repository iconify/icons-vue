<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhq0jyybt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lhq0jyybt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pixel-head-and-shoulders" /></template>
