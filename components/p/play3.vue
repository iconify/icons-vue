<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rd4dqkbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rd4dqkbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:play3" /></template>
