<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gn19yrb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gn19yrb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:smiley-smirk-solid" /></template>
