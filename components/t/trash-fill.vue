<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv4f0bbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="nv4f0bbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:trash-fill" /></template>
