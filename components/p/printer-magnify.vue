<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsll_2ggj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsll_2ggj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:printer-magnify" /></template>
