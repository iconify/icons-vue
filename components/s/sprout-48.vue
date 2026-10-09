<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o51dot6hb.css';
import '../../css/y/ybcmecbwb.css';
import '../../css/r/r9ac0nb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o51dot6hb"/><path class="ybcmecbwb"/><path class="r9ac0nb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sprout-48" /></template>
