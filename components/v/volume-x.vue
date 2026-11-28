<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu9ts_2cx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yu9ts_2cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:volume-x" /></template>
