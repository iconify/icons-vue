<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kkarr2bij.css';
import '../../css/c/ctcoo0l_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kkarr2bij"/><path class="ctcoo0l_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:parking-48-bold" /></template>
