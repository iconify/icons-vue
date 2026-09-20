<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o81h3dbhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o81h3dbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wolf-head-and-exclamation-point" /></template>
