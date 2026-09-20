<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7lw6ii2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z7lw6ii2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:ruff" /></template>
