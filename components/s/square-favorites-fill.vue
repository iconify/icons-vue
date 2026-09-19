<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq16369sx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="fq16369sx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-favorites-fill" /></template>
