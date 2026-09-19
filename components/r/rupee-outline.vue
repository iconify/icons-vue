<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdf057bks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="tdf057bks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:rupee-outline" /></template>
