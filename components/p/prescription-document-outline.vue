<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1v2czlmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="x1v2czlmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:prescription-document-outline" /></template>
