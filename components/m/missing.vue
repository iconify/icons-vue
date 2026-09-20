<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmtnt-_tb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zmtnt-_tb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:missing" /></template>
