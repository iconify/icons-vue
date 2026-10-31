<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjg_cfqen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjg_cfqen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tree-fill-round" /></template>
