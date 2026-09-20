<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylvmur2no.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ylvmur2no"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:motorcycle-filled" /></template>
