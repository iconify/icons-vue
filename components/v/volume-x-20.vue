<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yslz4fbvt.css';
import '../../css/i/ik3zd0b_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yslz4fbvt"/><path class="ik3zd0b_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:volume-x-20" /></template>
