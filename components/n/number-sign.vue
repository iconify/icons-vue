<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9_1y9bos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="i9_1y9bos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:number-sign" /></template>
