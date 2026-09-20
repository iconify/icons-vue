<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg_c-ubvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dg_c-ubvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:tasks-done" /></template>
