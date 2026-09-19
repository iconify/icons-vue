<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8u5an_lr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="s8u5an_lr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:minus-circle" /></template>
