<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c97p6wa7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c97p6wa7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:textalign-justifyleft-filled" /></template>
