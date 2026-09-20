<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecy_txqvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecy_txqvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:scales-2-line" /></template>
