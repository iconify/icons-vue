<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imduh9bzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="imduh9bzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:rss-symbol-solid" /></template>
