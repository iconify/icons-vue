<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f687inzts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":768,"height":659};
const content = `<path class="f687inzts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:twitter" /></template>
