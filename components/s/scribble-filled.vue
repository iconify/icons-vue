<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8zyaebmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e8zyaebmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:scribble-filled" /></template>
