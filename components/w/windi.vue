<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye5sjf4mn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ye5sjf4mn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:windi" /></template>
