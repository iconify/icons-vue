<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7va7rbxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":679,"height":680};
const content = `<path class="d7va7rbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:notify" /></template>
