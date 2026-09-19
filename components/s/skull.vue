<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dy8pq3bio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dy8pq3bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:skull" /></template>
