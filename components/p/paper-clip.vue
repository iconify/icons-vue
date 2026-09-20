<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-mj0x9-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w-mj0x9-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:paper-clip" /></template>
