<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jiwv_cb8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":384};
const content = `<path class="jiwv_cb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:shuffle" /></template>
