<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hoi7d2btf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hoi7d2btf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:up-fill" /></template>
