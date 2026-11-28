<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yi84ie6ix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yi84ie6ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:mail-x" /></template>
