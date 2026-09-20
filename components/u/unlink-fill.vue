<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugu7h1-mz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugu7h1-mz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:unlink-fill" /></template>
