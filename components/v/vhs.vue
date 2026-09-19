<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gby4ftqcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gby4ftqcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:vhs" /></template>
