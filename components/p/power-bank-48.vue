<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6k2ncbcg.css';
import '../../css/a/aemftobud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k6k2ncbcg"/><path class="aemftobud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:power-bank-48" /></template>
