<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdzwg8bxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wdzwg8bxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:shop-window" /></template>
