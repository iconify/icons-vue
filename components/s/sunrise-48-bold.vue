<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srxxy_b0g.css';
import '../../css/b/b9waewb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="srxxy_b0g"/><path class="b9waewb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sunrise-48-bold" /></template>
