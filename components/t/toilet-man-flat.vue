<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlptpho3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jlptpho3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:toilet-man-flat" /></template>
