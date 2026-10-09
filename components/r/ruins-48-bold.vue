<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihmii9b0s.css';
import '../../css/s/shk-1412s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ihmii9b0s"/><path class="shk-1412s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ruins-48-bold" /></template>
