<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5vo_hbwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="h5vo_hbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:quran" /></template>
