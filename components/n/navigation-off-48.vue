<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es3sj_btn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="es3sj_btn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:navigation-off-48" /></template>
