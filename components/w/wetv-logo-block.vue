<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzmwwebxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kzmwwebxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:wetv-logo-block" /></template>
