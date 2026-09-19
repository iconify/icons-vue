<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1nfcimdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":778,"height":739};
const content = `<path class="d1nfcimdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:starempty" /></template>
