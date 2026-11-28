<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srw_o6t-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srw_o6t-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:safe" /></template>
