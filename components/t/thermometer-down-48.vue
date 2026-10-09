<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqdv09daf.css';
import '../../css/i/ieq7_db9f.css';
import '../../css/e/egp_zuxqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hqdv09daf"/><path class="ieq7_db9f"/><path class="egp_zuxqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermometer-down-48" /></template>
