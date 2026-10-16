<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3gk-cbll.css';
import '../../css/e/etgb51bju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m3gk-cbll"/><path class="etgb51bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:secondary-substation-48" /></template>
