<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp36uggzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gp36uggzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:menu" /></template>
