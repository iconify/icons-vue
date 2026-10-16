<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0oa-qzdz.css';
import '../../css/d/dmf6wbcjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c0oa-qzdz"/><path class="dmf6wbcjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:user-round-20-bold" /></template>
