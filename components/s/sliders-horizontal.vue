<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7_2a2mjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7_2a2mjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:sliders-horizontal" /></template>
