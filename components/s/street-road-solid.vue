<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmtsn8bkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cmtsn8bkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:street-road-solid" /></template>
