<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrjnvkbuz.css';
import '../../css/x/xqit6kboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lrjnvkbuz"/><path class="xqit6kboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:negative-price-48" /></template>
