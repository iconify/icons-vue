<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9d61z38w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9d61z38w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:shield" /></template>
