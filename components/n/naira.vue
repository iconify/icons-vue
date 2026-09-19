<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8w8wzblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="i8w8wzblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:naira" /></template>
