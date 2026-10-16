<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw3x_bcqz.css';
import '../../css/y/ywzq7itsb.css';
import '../../css/w/wz0-7abar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lw3x_bcqz"/><path class="ywzq7itsb"/><path class="wz0-7abar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:voltage-source-48" /></template>
