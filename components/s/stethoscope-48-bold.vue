<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixi9bvbgc.css';
import '../../css/e/eqftyninf.css';
import '../../css/g/gc8-e8__z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ixi9bvbgc"/><path class="eqftyninf"/><path class="gc8-e8__z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:stethoscope-48-bold" /></template>
