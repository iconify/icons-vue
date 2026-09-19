<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-bnilbao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="i-bnilbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:sort-up-circle-fill" /></template>
