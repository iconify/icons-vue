<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybbuh2wlg.css';
import '../../css/w/wnxmmacan.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ybbuh2wlg"/><path class="wnxmmacan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:negative-price-20-bold" /></template>
