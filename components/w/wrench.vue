<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyxh5zbqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yyxh5zbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:wrench" /></template>
