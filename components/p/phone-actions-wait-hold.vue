<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sofr25-sz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sofr25-sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:phone-actions-wait-hold" /></template>
