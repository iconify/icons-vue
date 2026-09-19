<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v83bsjbfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v83bsjbfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:ryo" /></template>
