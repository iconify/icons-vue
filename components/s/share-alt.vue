<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8yi8ab8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="h8yi8ab8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:share-alt" /></template>
