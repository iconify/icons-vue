<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfic2tbud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfic2tbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:stove" /></template>
