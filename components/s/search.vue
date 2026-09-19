<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emc2ozcpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="emc2ozcpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:search" /></template>
