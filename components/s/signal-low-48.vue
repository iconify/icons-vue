<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbe-n9nml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xbe-n9nml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:signal-low-48" /></template>
