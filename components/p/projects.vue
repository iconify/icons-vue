<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypo4zjzwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ypo4zjzwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:projects" /></template>
