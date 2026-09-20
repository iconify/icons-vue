<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eevgm_byn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eevgm_byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:warm-up-3-fill" /></template>
