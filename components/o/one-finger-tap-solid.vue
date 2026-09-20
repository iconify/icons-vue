<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkyaeo7fi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jkyaeo7fi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:one-finger-tap-solid" /></template>
