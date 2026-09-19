<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oknd-gnfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oknd-gnfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:xml" /></template>
