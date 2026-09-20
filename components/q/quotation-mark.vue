<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lu8r0xb4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lu8r0xb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:quotation-mark" /></template>
