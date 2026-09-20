<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld6a4jbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ld6a4jbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:up-fill" /></template>
