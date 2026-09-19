<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qflp29d0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qflp29d0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:peace2x-outline" /></template>
