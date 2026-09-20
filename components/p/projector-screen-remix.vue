<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk5-r5guu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="sk5-r5guu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:projector-screen-remix" /></template>
