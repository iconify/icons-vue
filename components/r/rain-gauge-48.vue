<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzojfwbzi.css';
import '../../css/x/xym1wwbma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uzojfwbzi"/><path class="xym1wwbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rain-gauge-48" /></template>
