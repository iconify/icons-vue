<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr_q1qn4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wr_q1qn4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:zoom-in-filled" /></template>
