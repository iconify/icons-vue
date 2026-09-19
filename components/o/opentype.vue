<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8a8frnyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i8a8frnyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:opentype" /></template>
