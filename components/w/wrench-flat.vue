<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyh6kobku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wyh6kobku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:wrench-flat" /></template>
