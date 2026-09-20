<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cou3nsbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cou3nsbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:rotate-angle-45-remix" /></template>
