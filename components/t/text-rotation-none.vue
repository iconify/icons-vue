<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsk6of0ie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fsk6of0ie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:text-rotation-none" /></template>
