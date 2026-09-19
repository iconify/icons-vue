<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af-a9mxeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="af-a9mxeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:prescription" /></template>
