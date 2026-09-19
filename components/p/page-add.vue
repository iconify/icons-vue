<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lots55p-n.css';
import '../../css/p/psm-cjbgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="lots55p-n"/><path class="psm-cjbgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:page-add" /></template>
