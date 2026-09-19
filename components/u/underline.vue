<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a--ttxgga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a--ttxgga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:underline" /></template>
