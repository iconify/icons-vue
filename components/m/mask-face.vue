<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo7lrcqop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="uo7lrcqop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:mask-face" /></template>
