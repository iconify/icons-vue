<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz9c80bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fz9c80bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:tune-adjust-volume-remix" /></template>
