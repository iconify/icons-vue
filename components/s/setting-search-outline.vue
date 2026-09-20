<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs99e4b_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xs99e4b_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:setting-search-outline" /></template>
