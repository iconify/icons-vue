<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbf869b7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="lbf869b7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:wmo4680-89" /></template>
