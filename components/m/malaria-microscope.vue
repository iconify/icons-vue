<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-o8rwb8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="u-o8rwb8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:malaria-microscope" /></template>
