<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd7g7_byt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hd7g7_byt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:paint-roller" /></template>
