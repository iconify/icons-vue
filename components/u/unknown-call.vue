<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ormd75vrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ormd75vrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:unknown-call" /></template>
