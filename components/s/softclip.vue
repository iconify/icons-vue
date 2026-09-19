<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_wb2n3xb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="i_wb2n3xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:softclip" /></template>
