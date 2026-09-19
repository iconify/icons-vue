<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/voq30zbfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="voq30zbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:virus-alt" /></template>
