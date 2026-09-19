<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8h7at49z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o8h7at49z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:webassembly" /></template>
