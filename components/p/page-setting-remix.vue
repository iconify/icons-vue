<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayp-n_9at.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ayp-n_9at"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:page-setting-remix" /></template>
