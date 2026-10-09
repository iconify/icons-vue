<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlsrljbwz.css';
import '../../css/k/ko3mi2bbn.css';
import '../../css/b/bc05qdnjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rlsrljbwz"/><path class="ko3mi2bbn"/><path class="bc05qdnjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shield-x-48" /></template>
