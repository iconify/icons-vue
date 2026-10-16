<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrjnvkbuz.css';
import '../../css/d/drtg3332s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lrjnvkbuz"/><path class="drtg3332s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wholesale-price-48" /></template>
