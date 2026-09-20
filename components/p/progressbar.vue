<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw3ytlbiz.css';
import '../../css/d/dlp46-bmq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rw3ytlbiz"/><path class="dlp46-bmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:progressbar" /></template>
