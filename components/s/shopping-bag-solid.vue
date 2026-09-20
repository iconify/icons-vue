<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb70wwb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yb70wwb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:shopping-bag-solid" /></template>
