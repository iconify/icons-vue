<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae0qi1bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ae0qi1bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:r-outline" /></template>
