<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9qb4hlpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="v9qb4hlpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:virus" /></template>
