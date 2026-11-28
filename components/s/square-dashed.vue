<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s146rvdmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s146rvdmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-dashed" /></template>
