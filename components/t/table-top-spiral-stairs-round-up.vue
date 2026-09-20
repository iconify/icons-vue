<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb521_b-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="zb521_b-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:table-top-spiral-stairs-round-up" /></template>
