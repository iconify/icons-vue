<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9wid4gvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="p9wid4gvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:medical-advice" /></template>
