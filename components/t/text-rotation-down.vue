<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_yn9fbtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h_yn9fbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:text-rotation-down" /></template>
