<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd275sbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="dd275sbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:snow-flake" /></template>
