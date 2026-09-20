<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omeljc3-r.css';
import '../../css/s/sz6wmubsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="omeljc3-r"/><path class="sz6wmubsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:table-and-two-chairs-umbrella" /></template>
