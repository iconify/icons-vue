<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvr2orbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zvr2orbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ppt" /></template>
