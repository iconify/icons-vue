<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd5zuubcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bd5zuubcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:text-color-line" /></template>
