<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5dfnsyvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="m5dfnsyvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:temple-alt" /></template>
