<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu_zzgnel.css';
import '../../css/h/hqyn3psnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vu_zzgnel"/><path class="hqyn3psnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:moon-full-48" /></template>
