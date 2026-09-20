<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn7x1rbud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bn7x1rbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:multiple-stars" /></template>
