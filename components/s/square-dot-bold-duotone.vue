<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er9_2_bjd.css';
import '../../css/v/vg928d-qd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="er9_2_bjd"/><path class="vg928d-qd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-dot-bold-duotone" /></template>
