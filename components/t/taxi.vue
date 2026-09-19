<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tujzozb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":1792};
const content = `<path class="tujzozb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:taxi" /></template>
