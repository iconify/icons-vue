<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qh7_ghbdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qh7_ghbdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:scale-outline" /></template>
