<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqqvt6lnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hqqvt6lnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:tauri-wordmark" /></template>
