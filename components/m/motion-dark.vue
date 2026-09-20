<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jarw_gnfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1103,"height":386};
const content = `<path class="jarw_gnfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:motion-dark" /></template>
