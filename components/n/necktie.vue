<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3r18vqzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i3r18vqzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:necktie" /></template>
