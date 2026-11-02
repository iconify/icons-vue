<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ug4lk-61w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug4lk-61w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tree-3-line" /></template>
