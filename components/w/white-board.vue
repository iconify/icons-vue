<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cutgkoy-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="cutgkoy-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:white-board" /></template>
