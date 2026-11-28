<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rll_-bcvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="rll_-bcvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:rock" /></template>
