<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qeolk1tpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qeolk1tpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:management-stockout-filled" /></template>
