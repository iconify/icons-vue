<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uystlt1uo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uystlt1uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:screen-curve-remix" /></template>
