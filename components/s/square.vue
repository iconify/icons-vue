<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xas4q0rmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<rect class="xas4q0rmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:square" /></template>
