<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l823r3h8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l823r3h8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sail-boat-wreck" /></template>
