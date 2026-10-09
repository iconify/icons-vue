<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkje3ybpz.css';
import '../../css/t/tje1i_bou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gkje3ybpz"/><path class="tje1i_bou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:search-48" /></template>
