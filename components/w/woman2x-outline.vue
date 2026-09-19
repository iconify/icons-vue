<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/su8br7b-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="su8br7b-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:woman2x-outline" /></template>
