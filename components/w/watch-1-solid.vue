<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsizip9ri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tsizip9ri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:watch-1-solid" /></template>
