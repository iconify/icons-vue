<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/faf4xenwi.css';
import '../../css/j/jz0kekbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="faf4xenwi"/><path class="jz0kekbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wapy-dev-light" /></template>
