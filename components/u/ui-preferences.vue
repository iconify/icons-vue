<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0g9j6bqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v0g9j6bqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:ui-preferences" /></template>
