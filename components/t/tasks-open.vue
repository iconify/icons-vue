<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csed-1b0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="csed-1b0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:tasks-open" /></template>
