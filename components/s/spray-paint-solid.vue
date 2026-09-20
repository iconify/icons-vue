<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc9v22bql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yc9v22bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:spray-paint-solid" /></template>
