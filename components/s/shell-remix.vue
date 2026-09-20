<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ech75ovsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ech75ovsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:shell-remix" /></template>
