<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-da5wbxh.css';
import '../../css/h/h1p0vrb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="n-da5wbxh"/><path clip-rule="evenodd" class="h1p0vrb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:nav-administration" /></template>
