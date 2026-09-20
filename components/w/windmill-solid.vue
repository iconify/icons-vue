<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp8rk1bgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yp8rk1bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:windmill-solid" /></template>
