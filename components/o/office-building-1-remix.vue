<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pod46obej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pod46obej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:office-building-1-remix" /></template>
