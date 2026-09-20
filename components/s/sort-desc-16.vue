<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3s6o4b0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c3s6o4b0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:sort-desc-16" /></template>
