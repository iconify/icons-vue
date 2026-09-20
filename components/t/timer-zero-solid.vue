<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8mbo0bbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d8mbo0bbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:timer-zero-solid" /></template>
