<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc5u-tbli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xc5u-tbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:square-root-20" /></template>
