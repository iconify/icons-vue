<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqrl-diou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xqrl-diou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:time-two-outline" /></template>
