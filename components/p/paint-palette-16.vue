<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idcnk1b5s.css';
import '../../css/x/xqadazbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="idcnk1b5s"/><path clip-rule="evenodd" class="xqadazbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:paint-palette-16" /></template>
