<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh97r9dck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":384};
const content = `<path class="uh97r9dck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:skip-previous" /></template>
