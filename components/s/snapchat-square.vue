<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf856hbbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="uf856hbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:snapchat-square" /></template>
