<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-1da1b2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u-1da1b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:plus" /></template>
