<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edkn7ucuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="edkn7ucuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:printer-remix" /></template>
