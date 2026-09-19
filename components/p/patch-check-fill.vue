<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxdl9zb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jxdl9zb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:patch-check-fill" /></template>
