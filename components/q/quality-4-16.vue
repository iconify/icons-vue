<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh14dfj_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yh14dfj_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:quality-4-16" /></template>
