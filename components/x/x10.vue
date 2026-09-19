<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1exftzmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h1exftzmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:x10" /></template>
