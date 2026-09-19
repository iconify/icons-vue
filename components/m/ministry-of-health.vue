<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvjn01b8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qvjn01b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ministry-of-health" /></template>
