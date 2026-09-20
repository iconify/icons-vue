<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es6v1qf0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="es6v1qf0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:tsunami" /></template>
