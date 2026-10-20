<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5ttvzsqn.css';
import '../../css/c/cnq1mrb_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t5ttvzsqn"/><path class="cnq1mrb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tab-key-48" /></template>
