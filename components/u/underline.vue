<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxx0zybpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":666,"height":681};
const content = `<path class="rxx0zybpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:underline" /></template>
