<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_6rajbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g_6rajbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:puzzle-piece" /></template>
