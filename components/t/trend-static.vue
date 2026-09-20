<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pace_-bvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="pace_-bvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:trend-static" /></template>
