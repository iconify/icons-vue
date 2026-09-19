<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vr76icdak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vr76icdak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:scheme" /></template>
