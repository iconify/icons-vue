<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hekdg5bwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hekdg5bwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:type-bold" /></template>
