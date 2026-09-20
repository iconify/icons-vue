<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/st0wm4bnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="st0wm4bnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:shield-ai" /></template>
