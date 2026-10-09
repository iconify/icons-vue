<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rchvxnb6e.css';
import '../../css/i/i_vwc81mr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rchvxnb6e"/><path class="i_vwc81mr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:spirit-level-48" /></template>
