<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv-yu1hyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xv-yu1hyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:refresh-done-outline" /></template>
