<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9_ow_xmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9_ow_xmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:restart-line" /></template>
