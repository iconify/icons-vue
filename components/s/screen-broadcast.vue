<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnm0peb1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="vnm0peb1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:screen-broadcast" /></template>
