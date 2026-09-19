<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8g3esbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o8g3esbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:patch" /></template>
