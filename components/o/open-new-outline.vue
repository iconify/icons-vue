<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n96p5pben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n96p5pben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:open-new-outline" /></template>
