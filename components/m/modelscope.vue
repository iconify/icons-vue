<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9j2btb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9j2btb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:modelscope" /></template>
