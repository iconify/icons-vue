<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_2hme5xx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v_2hme5xx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:popcorn-remix" /></template>
