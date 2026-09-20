<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6te2lb2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g6te2lb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:user-multiple-circle-solid" /></template>
