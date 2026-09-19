<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iogzqd00i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iogzqd00i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:prompt" /></template>
