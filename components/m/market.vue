<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_xoy_top.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":650,"height":800};
const content = `<path class="p_xoy_top"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:market" /></template>
