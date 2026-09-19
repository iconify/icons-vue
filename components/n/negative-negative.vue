<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb7732w4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="wb7732w4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:negative-negative" /></template>
