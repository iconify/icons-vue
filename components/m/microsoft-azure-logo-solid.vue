<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt5mmebdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lt5mmebdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:microsoft-azure-logo-solid" /></template>
