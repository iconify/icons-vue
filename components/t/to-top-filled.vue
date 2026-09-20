<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wtxcc5b_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wtxcc5b_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:to-top-filled" /></template>
