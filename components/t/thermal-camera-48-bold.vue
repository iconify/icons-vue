<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n669t5b-i.css';
import '../../css/d/d1jrieb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n669t5b-i"/><path class="d1jrieb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:thermal-camera-48-bold" /></template>
