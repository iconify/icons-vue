<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqdic25tv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vqdic25tv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:search-outline" /></template>
