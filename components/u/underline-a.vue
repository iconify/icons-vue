<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xab97jbfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xab97jbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:underline-a" /></template>
