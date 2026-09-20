<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-vrd-b9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-vrd-b9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:pastebin" /></template>
