<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smjtv-oxv.css';
import '../../css/y/yixl0qbmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="smjtv-oxv"/><path class="yixl0qbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:presentation-48" /></template>
