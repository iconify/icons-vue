<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ytr-c8fjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ytr-c8fjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sun-line" /></template>
