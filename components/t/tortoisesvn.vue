<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c18d_gb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c18d_gb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:tortoisesvn" /></template>
