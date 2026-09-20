<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2jye-1ly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c2jye-1ly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:vip-consume-outline" /></template>
