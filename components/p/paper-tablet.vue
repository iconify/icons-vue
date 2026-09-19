<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7haebbsh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="u7haebbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:paper-tablet" /></template>
