<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3mqs9bzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g3mqs9bzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:netflix-remix" /></template>
