<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc9lc3bdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nc9lc3bdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:screen-2-remix" /></template>
