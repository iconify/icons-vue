<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/toqre_blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="toqre_blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:page-break" /></template>
