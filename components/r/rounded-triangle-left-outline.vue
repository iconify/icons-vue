<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qcyejvb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qcyejvb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:rounded-triangle-left-outline" /></template>
