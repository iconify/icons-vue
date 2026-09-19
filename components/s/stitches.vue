<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk7lobb8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pk7lobb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:stitches" /></template>
