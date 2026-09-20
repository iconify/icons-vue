<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbbpg3bnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2.5,"top":-2};
const content = `<path class="wbbpg3bnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:vine" /></template>
