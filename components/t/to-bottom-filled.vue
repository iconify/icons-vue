<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6lc9g5bl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y6lc9g5bl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:to-bottom-filled" /></template>
