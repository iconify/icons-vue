<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w6ppj1_bt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="w6ppj1_bt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:provider-fst-outline" /></template>
