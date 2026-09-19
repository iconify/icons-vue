<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc8t2-v3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pc8t2-v3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:shader" /></template>
