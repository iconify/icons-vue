<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r61xc-b7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":318,"height":512};
const content = `<path class="r61xc-b7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:owl" /></template>
