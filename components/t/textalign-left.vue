<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu1uclb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xu1uclb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:textalign-left" /></template>
