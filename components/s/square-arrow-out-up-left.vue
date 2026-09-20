<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz_qq2r_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mz_qq2r_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:square-arrow-out-up-left" /></template>
