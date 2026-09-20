<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gky2je_zi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gky2je_zi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:tree-needleleaved" /></template>
