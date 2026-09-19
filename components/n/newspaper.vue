<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcunpjb6q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xcunpjb6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:newspaper" /></template>
