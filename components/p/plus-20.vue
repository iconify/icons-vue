<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/moibuabky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="moibuabky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:plus-20" /></template>
