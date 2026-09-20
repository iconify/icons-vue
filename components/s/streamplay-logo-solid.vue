<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn_rija9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tn_rija9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:streamplay-logo-solid" /></template>
