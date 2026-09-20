<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a64rdloha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="a64rdloha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:template" /></template>
