<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_cg_6x-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_cg_6x-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:microsoft-windows-logo-2" /></template>
