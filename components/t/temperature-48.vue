<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg26btbri.css';
import '../../css/i/iasbg5lvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lg26btbri"/><path class="iasbg5lvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:temperature-48" /></template>
