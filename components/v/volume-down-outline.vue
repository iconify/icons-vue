<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voct9micl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="voct9micl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:volume-down-outline" /></template>
