<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx3e_tbqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1920,"height":1472};
const content = `<path class="mx3e_tbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:stumbleupon" /></template>
