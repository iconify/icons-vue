<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd2d9rhru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pd2d9rhru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tooth-48" /></template>
