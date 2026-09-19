<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdek8tbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdek8tbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:rotate-left" /></template>
