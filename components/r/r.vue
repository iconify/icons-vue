<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trg-1n7hi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":287,"height":654};
const content = `<path class="trg-1n7hi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:r" /></template>
