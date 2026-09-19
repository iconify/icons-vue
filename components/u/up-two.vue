<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c16rm2tya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c16rm2tya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:up-two" /></template>
