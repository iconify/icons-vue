<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdjqu4-xy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="bdjqu4-xy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:snowcapped-mountain-saddle" /></template>
