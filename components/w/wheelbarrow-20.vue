<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh_53abzu.css';
import '../../css/i/ijjhc3b5x.css';
import '../../css/u/uv47p4bdr.css';
import '../../css/f/f3itb8bvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lh_53abzu"/><path class="ijjhc3b5x"/><path class="uv47p4bdr"/><path class="f3itb8bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wheelbarrow-20" /></template>
