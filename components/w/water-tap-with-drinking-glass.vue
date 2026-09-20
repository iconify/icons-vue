<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr0ri2bsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="jr0ri2bsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:water-tap-with-drinking-glass" /></template>
