<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3342lbzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="d3342lbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:tray-full" /></template>
