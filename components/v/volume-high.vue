<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb94sgb1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="wb94sgb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:volume-high" /></template>
