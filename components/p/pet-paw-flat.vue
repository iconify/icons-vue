<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0w6l0kta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p0w6l0kta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:pet-paw-flat" /></template>
