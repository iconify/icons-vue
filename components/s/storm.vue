<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d54afjkli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d54afjkli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:storm" /></template>
