<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq0mikcbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tq0mikcbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorcycle-and-dollar" /></template>
