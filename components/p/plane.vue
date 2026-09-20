<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gk-lxkbeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gk-lxkbeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:plane" /></template>
