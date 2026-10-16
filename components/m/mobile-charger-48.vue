<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2fzm2btn.css';
import '../../css/y/y740_r6rb.css';
import '../../css/g/g_7g0l_kn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h2fzm2btn"/><path class="y740_r6rb"/><path class="g_7g0l_kn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mobile-charger-48" /></template>
