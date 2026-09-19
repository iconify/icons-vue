<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwps5fmjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bwps5fmjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:page-down-solid" /></template>
