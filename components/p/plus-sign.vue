<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_hak7-9q.css';
import '../../css/n/n8g0hetvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="y_hak7-9q"/><path class="n8g0hetvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:plus-sign" /></template>
