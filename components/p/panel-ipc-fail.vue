<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yybd16bsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="yybd16bsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:panel-ipc-fail" /></template>
