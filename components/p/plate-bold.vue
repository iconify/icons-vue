<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvv1albfv.css';
import '../../css/c/c8g41rsjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvv1albfv"/><path clip-rule="evenodd" class="c8g41rsjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:plate-bold" /></template>
