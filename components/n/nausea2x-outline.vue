<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqe6q6hbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fqe6q6hbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:nausea2x-outline" /></template>
