<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1a8b3mdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="j1a8b3mdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:syringe2x-outline" /></template>
