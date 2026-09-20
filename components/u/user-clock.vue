<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1p4-imiy.css';
import '../../css/f/fbmp7wgwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k1p4-imiy"/><path class="fbmp7wgwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:user-clock" /></template>
