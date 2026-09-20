<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbgk0ibde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbgk0ibde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:move-horizontal" /></template>
