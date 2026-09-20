<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpp3vpbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tpp3vpbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:user-group" /></template>
