<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9f7b2xcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k9f7b2xcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:up-square" /></template>
