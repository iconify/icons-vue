<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/leutjaccr.css';
import '../../css/k/kogtqeljo.css';
import '../../css/a/av7sw4bua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="leutjaccr"/><path class="kogtqeljo"/><path class="av7sw4bua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tea-cup-20" /></template>
