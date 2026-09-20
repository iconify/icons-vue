<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qt4jjhbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qt4jjhbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:syringe-remix" /></template>
