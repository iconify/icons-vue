<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg95nlblw.css';
import '../../css/k/kbgev3boj.css';
import '../../css/i/ihmii9b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gg95nlblw"/><path class="kbgev3boj"/><path class="ihmii9b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:suction-bucket-48-bold" /></template>
