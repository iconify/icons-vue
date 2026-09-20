<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usmti8bmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="usmti8bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:scanner-bar-code-remix" /></template>
