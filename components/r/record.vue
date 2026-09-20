<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z62y6x8ho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z62y6x8ho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:record" /></template>
