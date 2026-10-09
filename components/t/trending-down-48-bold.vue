<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtakimb5j.css';
import '../../css/q/qnyuvicip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qtakimb5j"/><path class="qnyuvicip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:trending-down-48-bold" /></template>
