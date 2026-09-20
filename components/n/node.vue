<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipy4p1jwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ipy4p1jwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:node" /></template>
