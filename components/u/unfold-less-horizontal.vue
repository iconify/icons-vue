<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqfje-b4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqfje-b4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:unfold-less-horizontal" /></template>
