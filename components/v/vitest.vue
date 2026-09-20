<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4dstr52f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a4dstr52f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:vitest" /></template>
