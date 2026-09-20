<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uexsjcbrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uexsjcbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:text-flow-rows-solid" /></template>
