<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie6g9hbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ie6g9hbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:tv" /></template>
