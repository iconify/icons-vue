<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmuenm5kt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qmuenm5kt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shield-off-48-bold" /></template>
