<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnnpbobrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mnnpbobrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:mammogram-outline" /></template>
