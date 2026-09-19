<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld3frub9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ld3frub9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:pancreas" /></template>
