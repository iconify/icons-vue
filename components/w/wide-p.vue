<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kboz2db7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kboz2db7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wide-p" /></template>
