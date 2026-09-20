<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmy-ii47q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xmy-ii47q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:wifi-abnormal-outline" /></template>
