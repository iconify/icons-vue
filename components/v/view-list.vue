<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh22k8bct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":368,"height":384};
const content = `<path class="gh22k8bct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:view-list" /></template>
