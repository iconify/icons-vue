<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rloht9byo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="rloht9byo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:upload" /></template>
