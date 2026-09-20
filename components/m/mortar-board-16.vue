<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw3wkzbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sw3wkzbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:mortar-board-16" /></template>
