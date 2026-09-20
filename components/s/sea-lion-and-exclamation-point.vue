<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqoh3l0wu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="iqoh3l0wu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sea-lion-and-exclamation-point" /></template>
