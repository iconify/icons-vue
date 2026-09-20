<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eelxote3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="eelxote3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:wind-flow-1-remix" /></template>
