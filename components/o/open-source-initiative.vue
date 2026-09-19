<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8nnvpbac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i8nnvpbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:open-source-initiative" /></template>
