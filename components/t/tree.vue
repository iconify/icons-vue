<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uywb0kb_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uywb0kb_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:tree" /></template>
