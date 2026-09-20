<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mv8h0sugj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mv8h0sugj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sliders-2-vertical" /></template>
