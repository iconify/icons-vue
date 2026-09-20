<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/re64yvbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="re64yvbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:smiley-kiss-remix" /></template>
