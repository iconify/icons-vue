<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in_ua9bkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="in_ua9bkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:peace-symbol-remix" /></template>
