<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbw7f2xxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="dbw7f2xxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:sack-dollar" /></template>
