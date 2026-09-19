<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm44b4gnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="cm44b4gnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:vsco" /></template>
