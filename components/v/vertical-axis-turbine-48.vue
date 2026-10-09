<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_ca49boy.css';
import '../../css/z/zy7z76-2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d_ca49boy"/><path class="zy7z76-2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:vertical-axis-turbine-48" /></template>
