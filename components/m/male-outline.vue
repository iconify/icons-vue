<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rstag4bft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rstag4bft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:male-outline" /></template>
