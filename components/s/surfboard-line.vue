<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppk8ufbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppk8ufbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:surfboard-line" /></template>
