<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azivo7bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="azivo7bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:oncology" /></template>
